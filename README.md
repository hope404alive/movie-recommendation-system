
# Movie Recommendation System using TF-IDF and Cosine Similarity

This repository contains code for a movie recommendation system implemented using TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity. The system takes a movie title as input and recommends similar movies based on their content, which includes the movie title and genre.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: pandas, scikit-learn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-tfidf.git
   cd movie-recommendation-tfidf
   ```

2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn
   ```

### Usage

1. Run the `movierecommendations.ipynb` script to load the dataset, preprocess data, and create the recommendation system.

2. Use the `get_recommendations` function to get movie recommendations:
   ```python
   recommended_movies = get_recommendations("Avatar", cosine_sim, df)
   print(recommended_movies)
   ```

## Dataset

The dataset used in this project is available [here](https://raw.githubusercontent.com/YBI-Foundation/Dataset/main/Movies%20Recommendation.csv). It contains movie titles and genres.

## Credits and Applause

A special credit and applause to the **YBI Foundation** for providing the dataset used in this project. Their dedication to making valuable datasets available for educational and research purposes is greatly appreciated.

Learn more about the YBI Foundation and their initiatives by visiting their [website](https://www.ybifoundation.org/). Let's applaud their efforts in promoting learning and innovation!
