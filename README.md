# Netflix Movie Recommender

Discover your next binge worthy obsession with this stylish movie and series recommendation engine built using Streamlit, pandas, and machine learning!

### Features

- Search any Netflix movie or series
- Intelligent recommendations using TF-IDF + Cosine Similarity
- Beautiful Netflix-inspired dark theme with animations
- IMDb rating, genre, and summary for each suggestion
- Quick "More Info" Google link for every recommendation


## Streamlit App

![demo](https://via.placeholder.com/800x400.png?text=Demo+Screenshot)



## Technologies Used

- `Streamlit` – for creating the web interface
- `pandas` – for data manipulation
- `scikit-learn` – for TF-IDF vectorization and similarity calculation
- `HTML & CSS` – for Netflix style theming


## Dataset

The app uses a dataset named `NetflixDataset.csv` containing columns like:
- `Title`
- `Genre`
- `Tags`
- `Summary`
- `IMDb Score`
- `Image`

## How It Works

1. **Text Processing**: Merges genre, tags, and summary into a single string.
2. **Vectorization**: Applies TF-IDF to convert text into vectors.
3. **Similarity**: Uses cosine similarity to compare titles.
4. **Recommendation**: Returns the top 5 most similar titles (excluding the searched one).

## Run Locally

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/netflix-recommender.git
   cd netflix-recommender
