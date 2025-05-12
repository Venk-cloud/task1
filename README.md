 Netflix Titles Dataset Cleaning (November 2019)

This project performs data cleaning and preprocessing on the **Netflix Titles Dataset (November 2019)** using Python and the **Pandas** library. It includes common cleaning tasks such as handling missing values, removing duplicates, standardizing text, and converting date formats.

# Dataset

- **File name:** `netflix_titles_nov_2019.csv`
- **Source:** Netflix’s public catalog of titles
- **Description:** Contains information about Netflix shows and movies such as title, type, director, cast, country, date added, release year, etc.

##  Cleaning Steps Performed

1. **Load the dataset** using `pandas.read_csv()`
2. **Identify and handle missing values** using `.isnull()` and `.fillna()`
3. **Remove duplicate rows** using `.drop_duplicates()`
4. **Standardize text values** (e.g., lowercase country names, unified values like "USA", "UK")
5. **Convert date formats** to `datetime` using `pd.to_datetime()`
6. **Rename column headers** to lowercase and replace spaces with underscores
7. **Check and fix data types** (e.g., ensure `release_year` is an integer)
8. **Save the cleaned data** as `cleaned_netflix_titles.csv`

## How to Use

1. Clone the repo or download the files
2. Open `netflix_cleaning.ipynb` in Jupyter Notebook or Google Colab
3. Run the cells step by step to clean the dataset
4. Use `cleaned_netflix_titles.csv` for further analysis or visualizations

