# Tunify

Tunify is a music recommendation system that recommends songs similar to a seed song entered by the user. The system uses the Spotify Web API to search for songs and calculate similarity scores between songs based on their audio features.

## Usage

To use Tunify, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/Tunify.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Enter your Spotify API credentials in `recommend.py`
4. Run the application: `python app.py`
5. Open your web browser and go to `http://localhost:5000`

## Requirements

Tunify requires the following packages to be installed:

- Flask==2.0.2
- spotipy==2.19.0
- numpy==1.21.2
- scikit-learn==1.0.1

## Files

- `app.py`: Flask application that runs the web interface for Tunify.
- `recommend.py`: Contains the main function that uses the Spotify API to recommend similar songs.
- `templates/index.html`: HTML template for the home page.
- `templates/results.html`: HTML template for the results page.
- `static/main.css`: CSS stylesheet for the web interface.

## Future Improvements

- Implement user authentication to access personalized recommendations.
- Incorporate additional audio features and machine learning algorithms to improve song similarity scores.
- Add a music player component to the web interface to allow users to listen to recommended songs directly on the site.
