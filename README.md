# Spotify Data Analysis in Python
This project analyzes a dataset containing information about Spotify tracks and explores various music attributes.

The data is comprised of two CSV files:

- **tracks.csv**: Contains details about tracks such as name, popularity, duration, artist(s), and explicit content flag.
- **SpotifyFeatures.csv**: Provides additional features for each track, including genre and audio properties like danceability, energy, and acousticness.

This project utilizes Python libraries including **pandas, NumPy, seaborn, and matplotlib** for data manipulation, analysis, and visualization.

Here's a breakdown of the key aspects covered in this project:
## Data Loading and Cleaning:

- Loads data from CSV files into pandas DataFrames.
- Explores data for missing values and potential inconsistencies.

## Data Exploration and Analysis:

- Analyzes basic statistics of numerical features like popularity and duration.
- Identifies most and least popular songs based on user popularity ratings.
- Creates a correlation heatmap to understand relationships between audio features.
- Performs sampling to reduce computational costs for visualizations.
- Generates regression plots to explore relationships between specific features (e.g., loudness vs. energy, popularity vs. acousticness).

## Time Series Analysis:

- Extracts release dates from the 'tracks.csv' file and converts them into datetime format.
- Creates a distribution plot (histogram) to visualize the distribution of songs across different years since 1922.
- Generates a bar chart to analyze how average song duration has changed over the years.
- Plots a line graph to depict the average duration of songs year-wise.

## Genre Analysis:

- Creates a bar chart to compare the average duration of songs across various genres.
- Identifies the top five most popular music genres based on user popularity ratings.

This project provides valuable insights into music trends and user preferences on Spotify. Feel free to explore the code further, customize visualizations, and delve deeper into specific genres or audio features.

#### Datasets can be found at:
- For [tracks.csv](https://www.kaggle.com/datasets/lehaknarnauli/spotify-datasets)
- For [SpotifyFeatures.csv](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db)
