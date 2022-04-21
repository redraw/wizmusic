# wizmusic

Update your WiZ light color based on the track playing in Spotify.

## Install
```
pip install wizmusic
```

## Usage

Create a Spotify app, and set the following env vars in your shell,
- `SPOTIPY_CLIENT_ID`
- `SPOTIPY_CLIENT_SECRET`
- `SPOTIPY_REDIRECT_URI`

Find your WiZ bulb IP address and run,

```
wizmusic -H <wiz-ip>
```
