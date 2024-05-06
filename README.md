# Data Analysis with New York Times and TMDB Data

## Background

In this project, we aimed to analyze movie reviews from the New York Times and gather additional movie data from The Movie Database (TMDB). The analysis involved collecting movie reviews from the New York Times API, extracting relevant information, querying TMDB for additional movie details, merging the datasets, and performing data cleaning and analysis.

## Task List

1. **Combine and Clean the Data:**
   - Imported movie reviews data from the New York Times API.
   - Filtered movie reviews with specific criteria.
   - Converted the "invoice_date" column to a datetime data type.
   - Retrieved movie reviews published between specific dates.
   - Converted the retrieved data into a pandas DataFrame.
   - Extracted the title from the "headline.main" column and saved it to a new column "title".
   - Extracted 'name' and 'value' from items in the "keywords" column and fixed the column format.

2. **TMDB Data Retrieval and Processing:**
   - Prepared The Movie Database query.
   - Retrieved additional movie details from TMDB using the movie titles extracted from the New York Times data.
   - Processed the TMDB data to extract relevant information such as genres, spoken languages, and production countries.

3. **Merge Datasets:**
   - Merged the New York Times reviews and TMDB DataFrames on the "title" column.

4. **Data Cleaning:**
   - Removed duplicate rows and reset the index.
   - Dropped unnecessary columns such as "byline.person" from the merged DataFrame.
   - Exported the cleaned and merged data to a CSV file without the index.

## Software Used

- Python (with libraries: requests, time, dotenv, pandas, json)
- New York Times API
- The Movie Database (TMDB) API

## Instructions

- Before running the code, ensure you have set up the necessary API keys and installed the required Python libraries.
- Run each code block sequentially to perform the data analysis tasks.
- Check the README.md file in the project repository for detailed instructions on setting up the environment, running the code, and interpreting the results.

