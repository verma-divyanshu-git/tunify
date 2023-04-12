# Tunify

Tunify is a spotify music recommendation system that suggests songs similar to a user-provided seed song. This project uses the Spotify API to obtain audio features of songs and calculate similarity scores between the seed song and other songs in the Spotify database.

## Getting Started

### Prerequisites
To run this project, you will need the following:

- A Spotify Developer account
- Jupyter Notebook
- Python 3
- Spotipy library (can be installed via pip)

### Installing
1. Clone the repository to your local machine
2. Install the required packages using pip: `pip install spotipy`

## Usage
1. Open the Jupyter Notebook file, `final_file.ipynb`
2. Input the name of a seed song when prompted
3. The program will output a list of 5 songs similar to the seed song, along with their Spotify URLs and similarity scores

## Future Development
- Deploy Tunify as a web app using Flask or another web framework
- Improve the recommendation algorithm by taking into account genre, language, and other factors
- Allow users to play recommended songs directly within the app
- Integration with user's Spotify account to access their personal playlists and listening history

## Acknowledgements
This project was created using the Spotipy library, which provides a Python interface to the Spotify Web API. The library was developed by Paul Lamere and is available on [GitHub](https://github.com/spotipy-dev/spotipy).

## Contributing
Pull requests are welcome.
