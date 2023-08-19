# Auto_Shuffle_Spotify
*Spotify Playlist Shuffler and Backup Script*

Description:

This app retrieves playlists for a user from their Spotify account, shuffles the tracks within each playlist, overwrites the shuffled playlists back to Spotify, and creates backups of the original playlists in a zipped JSON format.

Dependencies:
1. spotipy
2. python-dotenv

Install with pip, either directly or using the requirements.txt file:
```
pip install -r requirements.txt
```
```
pip install spotipy python-dotenv
```
Usage:
1. Ensure you have registered your application on the Spotify Developer Dashboard to obtain client credentials.
2. Create a .env file in the script directory containing:
```
    SPOTIPY_CLIENT_ID = <your_client_id>
    SPOTIPY_CLIENT_SECRET = <your_client_secret>
    SPOTIPY_REDIRECT_URI = <your_redirect_uri>
```
4. Run the script to shuffle playlists and create backups.
