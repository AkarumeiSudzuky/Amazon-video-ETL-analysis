# Amazon Prime Titles ETL Pipeline
## Objective
his project builds a simple **ETL (Extract, Transform, Load)** pipeline using Python to process data from the [Amazon Prime Titles dataset](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows). 
The final dataset is stored in CSV file and  PostgreSQL database for further use and analysis.
## 📌 Project Structure
1. **Extract**  
   Reads raw data from a CSV file (`amazon_prime_titles.csv`) using `pandas`.

2. **Transform**  
   Cleans and processes the dataset:
   - Removes null values
   - Parses date formats
   - Standardizes column values
   - Drops unnecessary fields

3. **Load**  
   Uploads the cleaned dataset into **CSV file** and  **PostgreSQL** database using `SQLAlchemy`.

4. **Power BI Report**
   - Distribution of Movies vs TV Shows
   - Content release trends over the years
   - Top genres and countries of production
   - Most frequent directors 

## 🚀 Technologies Used

- **Python 3**
- **Pandas** – for data manipulation
- **NumPy** – for numerical operations
- **SQLAlchemy** – for database connection
- **psycopg2** – PostgreSQL adapter for Python
- **Jupyter Notebook** – interactive development
- **Power Bi** - for interactive dashboard

