Audio_player_App
This is a simple React application for playing audio files with file upload functionality and a playlist.

## Features
File Upload: Users can upload audio files (e.g., mp3).
Playlist: Display a list of uploaded audio files.
Now Playing View: Show information about the currently playing audio file.
Playback Control: Users can play audio files from the playlist, and playback continues to the next file upon completion.
Persistence: When the page is reloaded, the app loads the last playing audio file and continues playing from the last position.
Getting Started
Clone the Repository git clone https://github.com/your-username/your-audio-player-app.git cd your-audio-player-app // navigate to the path
2.Install Dependencies npm i or npm i 3.Run the Application npm start Open http://localhost:3000 in your browser to view the app.

Folder Structure
src/: Contains the source code for the React app.
FileUpload.js: Component for file uploads.
Playlist.js: Component for displaying the playlist.
NowPlaying.js: Component for displaying the currently playing audio file.
AudioPlayer.js: Component for managing the HTML audio player.
App.js: Main component integrating other components.
public/: Contains public assets.
App.css: Styles for the app.
index.js: Entry point for the React app.
