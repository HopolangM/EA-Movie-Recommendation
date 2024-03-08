# EA-Movie-Recommendation

The recommendation system incorporates various data engineering techniques, including exploratory data analysis (EDA), feature engineering, and preprocessing steps.

## Exploratory Data Analysis (EDA)

### Rating Distribution

Visualizing the distribution of ratings to understand user preferences.

### Tag Frequencies

Exploring the frequency of tags associated with movies.

### Relevance Distribution

Analyzing the distribution of relevance scores for tags.

### Genre Distribution

Investigating the distribution of genres across the dataset.

### Summary Statistics

Displaying summary statistics of numerical features in the train data.

### IMDb Metadata

Exploring IMDb metadata for a specific movie, including information like cast, director, runtime, budget, and plot keywords.

### Missing Values

Checking and handling missing values in various datasets, including the train, test, tags, genome scores, IMDb data, links, and movies datasets.

## Data Engineering

### Genre-Based Features

Creating binary genre columns for each movie and counting the number of genres associated with each movie. Calculating the prevalence of each genre in the entire dataset.

### User-Based Features

Deriving user-based features such as average rating by user, number of ratings by user, and rating standard deviation by user.

### Movie-Based Features

Extracting movie-based features like average rating for each movie, number of ratings for each movie, and rating standard deviation for each movie.

### Temporal Features

Converting timestamps to datetime format, extracting temporal features like year and month, and calculating the average rating for each month.

### Tag-Based Features

Creating tag-based features using MultiLabelBinarizer for one-hot encoding and counting the number of tags associated with each movie. Utilizing tag genome scores to create additional features such as the average relevance score for each movie's associated tags.

### IMDb-Based Features

Including IMDb-based features like IMDb ratings for each movie.

## Link-Based Features

Utilizing IMDb and TMDB IDs to fetch external data and enrich the dataset.

## User-Item Interaction Features

Calculating the number of times a user has rated a movie.

## Other Features

There are mentions of user-user and item-item similarity features, length of movie titles as a feature, and average rating in a recent period, but the code snippets for these sections are not provided.

---


