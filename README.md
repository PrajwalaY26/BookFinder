# BookFinder

BookFinder is a project designed to load a dataset of books from an Excel file, store it in an SQLite database, and allow users to query the database based on their genre and rating preferences. The project uses Python, pandas, and SQLite for data handling and storage, and provides a simple interface for querying the books data.

## Technologies Used
### Python: 
The primary programming language used for this project.
### pandas: 
A powerful data manipulation library used to read the Excel file and process the dataset.
### SQLite: 
A lightweight, disk-based database used to store the books data.
### Google Colab: 
An online Jupyter notebook environment used to run the code and perform data analysis.
### tabulate: 
A library used to format the output of queries in a readable table format.

## Features
### Data Loading: 
Reads the dataset from an Excel file and processes it using pandas.
### Database Storage: 
Stores the processed data in an SQLite database.
### User Queries: 
Allows users to query the database based on genre and rating preferences.
### Formatted Output: 
Displays query results in a neatly formatted table.

## Setup Instructions
### Prerequisites
Before you begin, ensure you have the following installed:

### Python 3.x: 
The programming language used for this project. Download and install it from python.org.
### pandas: 
The data manipulation library. You can install it using pip:
```bash
pip install pandas
```
### openpyxl: 
An engine to read Excel files with pandas. Install it using pip:
```bash
pip install openpyxl
```
### SQLite: 
Included with Python by default, so no separate installation is required.
### tabulate: 
A library to format tables. Install it using pip:
```bash
pip install tabulate
```
### Google Colab: 
An online environment to run Jupyter notebooks. No installation is required, just access Google Colab.

## Instructions
1. Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/PrajwalaY26/bookfinder.git
```
2. Navigate to the Project Directory

```bash
cd bookfinder
```
3. Upload the Excel File

4. Ensure the Excel file (BooksDataSet.xlsx) is in the project directory. If not, upload it to Google Colab.

5. Run the Script

### Open the script in Google Colab or any Jupyter notebook environment and run the cells to execute the code. The script performs the following steps:

1. Verifies the existence of the Excel file.
2. Loads the dataset into a pandas DataFrame.
3. Processes the DataFrame to ensure correct column names.
4. Creates and populates an SQLite database with the books data.
5. Prompts the user to enter genre and rating preferences.
6. Queries the database based on user input and displays the results.
