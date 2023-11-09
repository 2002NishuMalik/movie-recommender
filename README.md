# Movie Recommender System

## Introduction
This project is a Movie Recommender System developed using Streamlit, Python, and the TMDB API. The system suggests movies based on user preferences, employing collaborative filtering to generate relevant recommendations.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/movie-recommender-system.git
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Obtain API Key:**
   - Obtain an API key from [TMDB](https://www.themoviedb.org/documentation/api).
   - Replace the placeholder in the `fetch_poster` function in `app.py` with your API key.

4. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Select a Movie:**
   - Choose a movie from the dropdown menu on the Streamlit web interface.

2. **Get Recommendations:**
   - Click the "Recommend" button to receive a list of recommended movies based on the selected one.

3. **View Recommendations:**
   - Explore the recommended movies along with their corresponding posters.

## Files

- **`app.py`**: Main Streamlit application script.
- **`movies_dict.pkl`**: Pickle file containing movie data.
- **`similarity.pkl`**: Pickle file containing similarity data.
- **`requirements.txt`**: List of dependencies required for the project.

## Credits

- The project utilizes movie data from [TMDB](https://www.themoviedb.org/).
- Developed with the help of [Streamlit](https://www.streamlit.io/).

## Acknowledgments

- Special thanks to [TMDB](https://www.themoviedb.org/) for providing comprehensive movie data.
- Inspiration and guidance drawn from [Streamlit](https://www.streamlit.io/) documentation.

Feel free to explore and enjoy personalized movie recommendations!

---

Remember to customize placeholders like `your-username` and provide any additional instructions specific to your project.
