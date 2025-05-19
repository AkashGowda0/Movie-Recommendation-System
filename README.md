# MovieMate AI

MovieMate AI is a Flask-based web application that allows users to explore movies, view detailed information, and perform sentiment analysis on movie reviews. It integrates TMDB API for movie data and uses TextBlob and DeepFace for sentiment and emotion analysis.

To set up the project manually, first clone the repository with `git clone https://github.com/yourusername/moviemate-ai.git` and navigate into the folder with `cd moviemate-ai`. Make sure you have Python 3.7 or higher installed on your machine (check with `python --version`). If not installed, download it from [python.org](https://www.python.org/downloads/).

Install the required Python libraries manually using pip by running the following commands:
pip install flask

pip install requests

pip install textblob

pip install deepface


Alternatively, if a `requirements.txt` file is included, you can run `pip install -r requirements.txt` to install all dependencies at once.

Next, obtain your TMDB API key from [TMDB Developer Portal](https://developer.themoviedb.org/) and open the `app.py` file in the project. Replace the placeholder `'your_tmdb_api_key'` with your actual TMDB API key in the configuration section.

Run the Flask application locally by executing `python app.py`. Open your browser and go to `http://127.0.0.1:5000` to access the app.

The project structure includes the main application file `app.py`, a `templates` folder containing HTML templates, a `static` folder for CSS, JavaScript, and images, and optionally a `requirements.txt` for dependencies.

You can search for movies by title, view detailed movie information, and see sentiment analysis on reviews (positive, negative, neutral). The app also optionally supports emotion detection with DeepFace.

Contributions are welcome! To contribute, fork the repo, create a feature branch, commit your changes, push the branch, and open a pull request.

This project is licensed under the MIT License.

For questions or support, open an issue or contact me at your.email@example.com.

Thank you for using MovieMate AI!
