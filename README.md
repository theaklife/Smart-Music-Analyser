#  Smart Music Analyzer

A lightweight, client-side web application that analyzes local music files to detect their genre and mood, then provides personalized song recommendations based on the detected genre. No server, no accounts, no subscriptions—just pure music discovery!

##  Features

- **Local File Analysis**: Upload any audio file (MP3, WAV, etc.) directly from your device.
- **Smart Genre Detection**: Uses metadata (ID3 tags) and filename keywords to determine the genre.
- **Curated Recommendations**: Get handpicked song suggestions matching the detected genre.
- **Spotify Integration**: Listen to track previews directly in the app via embedded Spotify players.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Offline-Friendly**: No internet required after the initial page load.

##  Supported Genres

- Phonk
- Trap
- Sad
- Love
- Pop
- Lofi
- Rock
- Indie

##  Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Metadata Extraction**: [jsmediatags](https://github.com/aadsm/jsmediatags)
- **Spotify Integration**: Spotify Embed API
- **Hosting**: GitHub Pages (or any static hosting service)

##  How to Use

1. **Upload a Music File**:
   - Click the "Choose Audio File" button and select an audio file from your device.

2. **Genre Detection**:
   - The app will automatically detect the genre from the file's metadata or filename.
   - You can also manually select a genre from the dropdown.

3. **Get Recommendations**:
   - The app will display a list of recommended songs matching the detected genre.
   - Click the Spotify embed to listen to a preview or open the song in Spotify.

##  Project Structure

```
smart-music-analyzer/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript logic
└── README.md           # Project documentation
```

##  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/theaklife/smart-music-analyzer.git
   ```

2. Open `index.html` in your browser:
   - Simply double-click the file or use a local server like Live Server (VS Code extension).

##  Deployment

Deploy the app to any static hosting service:
- [GitHub Pages](https://pages.github.com/)

##  Known Issues

- Some audio files may lack metadata, requiring fallback to filename analysis.
- Large files (>10MB) may cause slight delays in metadata extraction.

##  Future Enhancements

- **Machine Learning**: Integrate TensorFlow.js for audio waveform analysis.
- **Expanded Database**: Add more genres and songs.
- **User Preferences**: Save favorite genres/songs using localStorage.
- **PWA Support**: Convert to a Progressive Web App for offline use.

##  License

This project is open-source and available under the [MIT License](LICENSE).

Happy music discovery!
