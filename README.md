# Netflix Content Filtering and Analysis

## Overview
This project performs data processing, visualization, and content-based filtering for Netflix titles. The dataset includes various movie and TV show attributes such as title, director, cast, genre, description, and release date. The goal is to explore the dataset, visualize content distribution, and build a recommendation system based on text similarity.

## Features
- Loads and processes Netflix titles dataset.
- Cleans and preprocesses data by handling missing values and extracting date features.
- Visualizes dataset distributions, including content type counts and yearly additions.
- Implements a content-based filtering system using:
  - Keyword extraction with `rake-nltk`
  - Text vectorization using `CountVectorizer`
  - Cosine similarity for content recommendations

## Requirements
Install the necessary dependencies using:

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn rake-nltk nltk
```

## File Structure
- `netflix_titles.csv` - CSV file containing Netflix content metadata.
- `content_filtering.ipynb` - Jupyter Notebook for data processing and recommendation system.

## How to Run
1. Ensure the `netflix_titles.csv` file is in the working directory.
2. Open the Jupyter Notebook and execute the cells step by step.
3. The notebook will generate visualizations and recommendations based on the dataset.

## Explanation of Key Functions
### `bold(string)`
Displays bold text output in Markdown format.

### `pie_plot(cnt_srs, title)`
Generates a pie chart using Plotly.

### `load_data()`
Loads and preprocesses the dataset by handling missing values and extracting date features.

### `generate_visualizations()`
Creates various visualizations to analyze Netflix content distribution.

### `content_filtering()`
Performs content-based filtering by:
- Extracting keywords from descriptions.
- Vectorizing text data.
- Calculating cosine similarity to recommend similar content.

## Output
- Dataset visualizations showcasing trends in Netflix content.
- A recommendation system suggesting similar titles based on content attributes.

## License
This project is open-source and can be used for educational and research purposes.

