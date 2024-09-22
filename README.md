# Spotify Music Player App

This is a simple Spotify Music Player App built using HTML, CSS, and JavaScript. The app allows users to browse music genres, view playlists based on selected genres, and listen to individual tracks. The project leverages the **Spotify API** to fetch data.

## Features

- Fetch and display music genres using the Spotify API.
- Retrieve playlists based on a selected genre.
- Display track details including song title, artist, and album art.
- Use of modular JavaScript to separate UI, API, and app logic.
  
## How It Works

1. **API Module (`APIController`)**:
    - Handles communication with Spotify API.
    - Fetches access token using Client ID and Client Secret.
    - Retrieves genres, playlists, and track details.

2. **UI Module (`UIController`)**:
    - Manages the user interface.
    - Populates genres, playlists, and track details.
    - Provides methods to reset or update the DOM.

3. **App Module (`APPController`)**:
    - Coordinates between the API and UI modules.
    - Loads genres on page load.
    - Listens for user interactions such as genre selection and song play.

## Setup

### Prerequisites
To run this project, you will need:
- A **Spotify Developer Account** to get the API `clientId` and `clientSecret`.
- Basic knowledge of HTML, CSS, and JavaScript.

### Getting Started

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/spotify-music-player.git
    ```

2. Update the `clientId` and `clientSecret` in the code:
    ```javascript
    const clientId = 'your-client-id';
    const clientSecret = 'your-client-secret';
    ```

3. Open the `index.html` file in your browser to use the app.

## Technologies Used

- **HTML/CSS**: For structure and styling.
- **JavaScript**: For application logic and API integration.
- **Spotify API**: To fetch genres, playlists, and tracks.

## Acknowledgments

This project was created following a YouTube tutorial that helped me learn how to work with the Spotify API and implement various app functionalities.

## License

This project is licensed under the MIT License.
