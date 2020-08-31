# Musicterminal
Terminal application that search artists, albums and tracks and play music by using the Spotify REST API

### Setup
```shell
cd musicterminal
python3 -m venv venv
. musicterminal/bin/activate
pip install -r requirements.txt
cp config-example.yaml config.yaml
```

*Note* You need a premium account to reproduce music.

1. Create an musicterminal application in your Spotify developer account https://developer.spotify.com/dashboard/
1. Copy the client_id and client_secret to config.yaml
1. Hit ```python spotify_auth.py``` in your terminal and follow the steps to gtet the authorization.
1. Close yu browser window and stop the server.

### Usage
```
python app.py
```