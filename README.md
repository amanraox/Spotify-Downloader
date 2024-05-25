<h1 align="center">
  <b>Spotify Downloader</b>
</h1>

<b>A simple python script to download songs/albums/playlists from spotify.</b>


## Install and run
- Clone the repository:    
`git clone https://github.com/minkxx/SpotifyDownloader.git`
- Go to the cloned folder:    
`cd SpotifyDownloader`
- Get your [Necessary Variables](#Necessary-Variables)
- Create a file `config.py` and store them:    
`SPOTIFY_CLIENT_ID = "your client id"`
`SPOTIFY_CLIENT_SECRET = "your client secret"`
- Install the requirements:      
`pip install -U -r requirements.txt`
- Run the script and enter spotify track/album/playlist link to download on `songs/` folder:    
`python spotifyDownloader.py`

## Necessary Variables
- `SPOTIFY_CLIENT_ID` - Spotify client_id. Get it from [here](https://developer.spotify.com/dashboard/)
- `SPOTIFY_CLIENT_SECRET` - Spotify client_secret. Get it from [here](https://developer.spotify.com/dashboard/)
