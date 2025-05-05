🎥 Movie Recommender System
Welcome to the Movie Recommender System! This project uses collaborative filtering and content-based methods to recommend movies based on user-selected titles. The application is powered by Streamlit, pandas, and The Movie Database (TMDb) API to deliver an interactive and user-friendly experience.

🌟 Features
Movie Recommendations: Get personalized movie suggestions by selecting your favorite title.

Poster Previews: View posters for recommended movies for a visually immersive experience.

Intuitive Interface: Built with Streamlit, the UI is clean, responsive, and easy to navigate.

📂 Project Structure
app.py: Main script for the Streamlit web application. Handles user inputs, fetches movie data, and displays recommendations.

tmdb_5000_movies.csv: Dataset containing detailed information about movies, used for initial data preprocessing and model training.

movie_recommender_system.ipynb: Jupyter notebook with preprocessing and similarity matrix generation logic.

movie_list.pkl & similarity.pkl: Pickled files containing the movie dataset and precomputed similarity matrix.

🚀 How It Works
Data Loading: Preprocessed movie data and similarity matrix are loaded from .pkl files.

User Input: Select a movie from the dropdown menu.

Recommendation Algorithm:

Finds similar movies using the precomputed similarity matrix.

Fetches additional details (like posters) from TMDb API.

Display Results: Recommended movie titles and posters are displayed interactively.

🛠️ Setup Instructions
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/movie-recommender-system.git
cd movie-recommender-system
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Add your TMDb API key:

Replace the placeholder API key in app.py with your TMDb API key.

Get your API key here.

Run the app:

bash
Copy
Edit
streamlit run app.py
Open the local URL provided in the terminal to start using the app.

📊 Dataset
The tmdb_5000_movies.csv dataset is sourced from TMDb. It contains:

Movie Titles

Genres

Popularity Metrics

Overview & More


📬 Contact
For any questions or suggestions, feel free to reach out:

GitHub: https://github.com/harimurari27
