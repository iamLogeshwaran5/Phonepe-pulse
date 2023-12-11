
# Phonepe-pulse | Phonepe Pulse Dashboard Project

Phonepe Pulse Data Visualization and Exploration:
A User-Friendly Tool Using Streamlit and Plotly
____________________


## Overview

This project aims to extract, transform, and visualize data from the Phonepe Pulse GitHub repository. It involves scripting to fetch the data, transforming it into a suitable format, inserting it into a MySQL database, and creating an interactive dashboard using Python libraries like Pandas, Plotly, Streamlit, and mysql-connector-python.

## Tools and Technologies Used

- Python
- Pandas
- Plotly
- Streamlit
- mysql-connector-python
- MySQL


## Installation and Usage

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Follow the instructions in the `scripts/README.md` for data extraction, transformation, database insertion, and dashboard creation.
4. Run the application and access the dashboard locally or deploy it for public access.



## Steps Involved

### 1. Data Extraction

Clone the Phonepe Pulse GitHub repository using scripting to fetch the data and store it in CSV or JSON format.

### 2. Data Transformation

Utilize Python, Pandas, and other relevant libraries for data manipulation. This step includes cleaning, handling missing values, and formatting the data for analysis and visualization.

### 3. Database Insertion

Connect to a MySQL database using the `mysql-connector-python` library in Python. Insert the transformed data into the database using SQL commands.

### 4. Dashboard Creation

Use Plotly and Streamlit libraries in Python to design an interactive and visually appealing dashboard. Implement Plotly's geo map functions to display data on a map. Streamlit will provide a user-friendly interface with dropdown options for selecting different data facets.

### 5. Data Retrieval

Connect to the MySQL database using `mysql-connector-python`. Fetch the data into a Pandas dataframe to dynamically update the created dashboard.

### 6. Deployment

Ensure the solution is secure, efficient, and user-friendly. Thoroughly test the solution before deploying the dashboard publicly, making it accessible to users.


## Documentation

The detailed documentation for this project can be found [here](https://drive.google.com/file/d/1VBRecdnRpbutknJLNZQC4f1bc1eKWdsw/view).

## Dataset

The dataset used offical phonepe repo in this project can be accessed [here](https://github.com/PhonePe/pulse.git).

## Inspired From
- [Phonepe offical](https://www.phonepe.com/pulse/explore/transaction/2022/4/) - Description or explanation of how it inspired the project.




