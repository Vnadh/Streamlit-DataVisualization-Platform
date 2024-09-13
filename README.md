# Simple Data Dashboard

This is a web-based data visualization platform built using Streamlit. It allows users to upload a CSV file, preview the data, apply filters, and generate line plots for better data insights.

## Features

1. **CSV File Upload:** Upload your CSV file for data analysis.
2. **Data Preview:** See the first few rows of your dataset.
3. **Data Summary:** Get a statistical summary of the data.
4. **Data Filtering:** Filter the dataset based on column values.
5. **Data Visualization:** Plot data using line charts.

## Installation

1. Clone this repository or download the code.
2. Install the required dependencies:
   ```bash
   pip install streamlit pandas matplotlib
    ```
## 
Here’s the updated README.md with the new details you provided:

markdown
Copy code
# Simple Data Dashboard

This is a web-based data visualization platform built using Streamlit. It allows users to upload a CSV file, preview the data, apply filters, and generate line plots for better data insights.

## Features

1. **CSV File Upload:** Upload your CSV file for data analysis.
2. **Data Preview:** See the first few rows of your dataset.
3. **Data Summary:** Get a statistical summary of the data.
4. **Data Filtering:** Filter the dataset based on column values.
5. **Data Visualization:** Plot data using line charts.

## Installation

1. Clone this repository or download the code.
2. Install the required dependencies:
   ```bash
   pip install streamlit pandas matplotlib
   ```
## Usage
1. Run the Streamlit app:
```bash
   streamlit run app.py
   ```
2. Open your web browser and go to:
```bash
   http://localhost:8501
   ```
3.Upload your CSV file, filter the data, and generate plots.
## How It Works
1. **File Upload:** The platform accepts CSV files via the st.file_uploader() component.
2. **Data Preview:** The first few rows of the data are shown using st.write(df.head()).
3. **Data Summary:** Displays summary statistics using df.describe().
4. **Data Filtering:** Users can select a column and filter the dataset based on unique values from that column.
5. **Data Plotting:** Users can choose any two columns for x and y axes and generate line plots.
## Requirements
. Python 3.x
. Streamlit
. Pandas
. Matplotlib

