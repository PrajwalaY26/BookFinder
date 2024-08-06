# BookFinder

BookFinder is a project designed to load a dataset of books from an Excel file, store it in an SQLite database, and allow users to query the database based on their genre and rating preferences. The project uses Python, pandas, and SQLite for data handling and storage, and provides a simple interface for querying the books data.

## Integration of Python and SQLite
### Why Use SQLite?
SQLite is a lightweight, disk-based database that doesn’t require a separate server process, making it a perfect choice for small to medium-sized projects. It's included with Python, so no additional installation is needed.

### Linking Python with SQLite
Python's sqlite3 module allows for seamless integration with SQLite databases. Using pandas, we can easily read the Excel file and convert it into a format suitable for database insertion. The process involves:

1. Reading the Excel file using pandas to load the data into a DataFrame.
2. Cleaning and preparing the data by ensuring column names are correct and any unnecessary columns are removed.
3. Creating an SQLite database and defining the schema to store the book data.
4. Inserting data from the DataFrame into the SQLite database.
5. Querying the database based on user preferences, such as genre and rating, to retrieve and display relevant book information.
This approach ensures data integrity, provides efficient data storage, and allows for complex queries to be performed easily.

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

#### Python 3.x: 
The programming language used for this project. Download and install it from [python.org](https://www.python.org/).
#### pandas: 
The data manipulation library. You can install it using pip:
```bash
pip install pandas
```
#### openpyxl: 
An engine to read Excel files with pandas. Install it using pip:
```bash
pip install openpyxl
```
#### SQLite: 
Included with Python by default, so no separate installation is required.
#### tabulate: 
A library to format tables. Install it using pip:
```bash
pip install tabulate
```
#### Google Colab: 
An online environment to run Jupyter notebooks. No installation is required, just access [Google Colab](https://colab.research.google.com/).

## Instructions
### 1. Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/PrajwalaY26/bookfinder.git
```
### 2. Navigate to the Project Directory

```bash
cd bookfinder
```
### 3. Upload the Excel File

Ensure the Excel file (BooksDataSet.xlsx) is in the project directory. If not, upload it to Google Colab.

### 4. Run the Script

### Open the script in Google Colab or any Jupyter notebook environment and run the cells to execute the code. The script performs the following steps:

1. Verifies the existence of the Excel file.
2. Loads the dataset into a pandas DataFrame.
3. Processes the DataFrame to ensure correct column names.
4. Creates and populates an SQLite database with the books data.
5. Prompts the user to enter genre and rating preferences.
6. Queries the database based on user input and displays the results.

### 5. Using the Provided Database

The repository includes an SQLite database file (books.db) with pre-loaded book data. This file is provided so users can cross-check or verify their results against the pre-loaded data. You can upload this file to your working directory in Google Colab to use it directly.
