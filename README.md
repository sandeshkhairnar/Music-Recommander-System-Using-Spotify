# Music Recommender System

## Introduction

The Music Recommender System is a Python-based application that leverages Spotify's API to provide music recommendations to users. It utilizes trending playlist data from Spotify and employs recommendation algorithms to suggest songs based on user preferences. The system offers both content-based and hybrid recommendation approaches to enhance the user's music discovery experience.

## Setup

### Obtaining Spotify Credentials

Before using the Music Recommender System, you need to obtain the necessary credentials from Spotify for authentication. Follow these steps:

1. Go to the Spotify Developer Dashboard (https://developer.spotify.com/dashboard/) and log in or sign up for an account.
2. Create a new Spotify application.
3. Note down the Client ID and Client Secret provided by Spotify. These credentials will be used for authentication when accessing the Spotify API.

### Environment Setup

To set up the environment for running the Music Recommender System, you can follow these steps:

1. **Install Python:** If Python is not already installed on your system, you can download it from the official website [here](https://www.python.org/).

2. **Clone or Download the Project:** Clone or download the Music Recommender System project from the repository.

3. **Navigate to the Project Directory:** Open your command line interface (CLI) or terminal, navigate to the directory where you cloned or downloaded the Music Recommender System project.

4. **Create a Virtual Environment:** In the project directory, create a virtual environment to manage dependencies. You can do this using the following command:
    ```
    python -m venv venv
    ```
    This command will create a folder named `venv` in your project directory containing the virtual environment.

5. **Activate the Virtual Environment:**

    - **On Windows:**
        ```
        venv\Scripts\activate
        ```

    - **On macOS and Linux:**
        ```
        source venv/bin/activate
        ```
    Activating the virtual environment will ensure that the dependencies installed for this project do not conflict with other Python projects on your system.

6. **Install Required Dependencies:** Once the virtual environment is activated, install the required dependencies listed in the `requirements.txt` file using pip:
    ```
    pip install -r requirements.txt
    ```

Alternatively, if you prefer using Google Colab, you can upload the project files to your Google Drive and open the notebook using Google Colab. Then, you can run the notebook cells directly in the Colab environment.

## Process

1.Implemented Spotify API Integration:

- Utilized obtained Spotify credentials to authenticate with the Spotify API.
- Implemented functions to fetch music data from Spotify, such as trending playlists and track information.

2.Data Preprocessing:

- Cleaned and preprocessed the fetched music data.
- Extracted relevant features from the data, including track name, artists, album name, and audio features.

3.Implemented Recommendation Algorithms:

- Implemented content-based and hybrid recommendation approaches to generate personalized recommendations.

4.Generated Recommendations:

- Developed functions to generate music recommendations based on user input, such as song name or artist.
- Utilized implemented recommendation algorithms to generate recommendations.

5.Displayed Recommendations:

- Printed or displayed the generated recommendations to the user in a readable format.
- Included relevant information such as track name, artists, album name, and popularity.

![Screenshot 2024-05-25 032305](https://github.com/sandeshkhairnar/Music-Recommander-System-Using-Spotify/assets/145431558/487dfa82-fc38-495e-ada4-bc6412b32a01)

