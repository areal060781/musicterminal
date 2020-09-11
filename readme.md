# Music terminal
A simple terminal client that acts as a module wrapper for Spotify's REST API where users can search for artists, browse 
the artist's albums and tracks, and finally play a song in the user's active device, which can be a computer, mobile phone, 
or even a video game console.

* **OAuth**, Implement the two types of authentication flow that Spotify supports: the client credentials flow and the authorization flow
* **Request** to consume REST APIs
* User interface with **curses**

**Requirements**
- [x] Virtualenv
- [x] [A Spotify developer account](https://developer.spotify.com/dashboard/)

*NOTE:* You need a premium account to reproduce music

### Setup
Inside the project directory:
Create the virtual environment, activate it and install the dependencies
```shell
python3 -m venv venv
. musicterminal/bin/activate
pip install -r requirements.txt
```
Copy the configuration file
```
cp config-example.yaml config.yaml
```

1. Create an musicterminal application in your Spotify developer account 
1. Copy the client_id and client_secret to config.yaml
1. Hit ```python spotify_auth.py``` in your terminal and follow the steps to gtet the authorization.
1. Close yu browser window and stop the server.

### Run the application
```
python app.py
```