# Personalized-Playlist-Recommendation-System
 Here’s a tailored description for your project:  Personalized Playlist Recommendation System  This project is a recommendation system built to generate song suggestions exclusively within a user’s own Spotify playlist. Using the Spotify Developer API, the system retrieves audio feature data for all tracks in a specified playlist,.
Features and Approach:

Data Collection: The Spotify Developer API fetches songs from the user’s playlist, along with associated audio features like energy, danceability, tempo, and loudness.

In-Playlist Recommendations: For any song chosen within the playlist, the system suggests similar songs—also from the playlist—based on two primary methods:

k-Nearest Neighbors (k-NN): Calculates song similarity through feature vectors and suggests the closest matches within the playlist.
Cluster-Based Recommendations: Groups songs based on shared audio features, then recommends tracks within the same cluster, providing genre or mood-consistent options.
Visualization: A feature similarity visualization helps illustrate the closeness between the input song and the recommended tracks, giving insight into their shared characteristics.

By focusing on in-playlist recommendations, this system ensures that each suggestion is familiar yet varied, enhancing the listening experience within a personal music collection.


User can change the playlist here
(playlist_id = '5ABHKGoOzxkaa28ttQV9sE')
# Replace with your own Client ID and Client Secret
CLIENT_ID = ' '
CLIENT_SECRET = ' '
