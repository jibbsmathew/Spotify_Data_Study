# Spotify Song Valence Analysis and Recommendation

This code retrieves data from a Spotify playlist and analyzes the audio features of the tracks using the Spotify API and Python.

## Usage

1. Register an app on the Spotify for Developers dashboard to obtain a client ID and client secret
2. Insert your client ID and client secret into the script
3. Specify the playlist ID of the playlist you want to analyze (the ID is the series of letters and numbers after "/playlist/" in the playlist URL) 
4. Run the script to retrieve the playlist data and audio features
5. The data is stored in a Pandas DataFrame for analysis

## Analysis Ideas

Once you have the playlist data, here are some ideas for analysis:

- Visualize audio features like danceability, energy, acousticness, etc. over time or by album/artist
- Identify audio patterns like tempo, key signatures, etc.
- Apply machine learning models to cluster songs or make song recommendations
- Compare audio features between playlists to characterize different genres/moods
- Build predictive models to classify playlists or suggest additional tracks

There is a lot you can do once you have easy access to audio data!

## Libraries Used

- `spotipy` - Wrap the Spotify API
- `requests` - Make API calls 
- `pandas` - Store and analyze data
- `matplotlib` - Visualizations

## Author

Jeremy Mathew - Github @jibbsmathew

Let me know if you have any other questions!
