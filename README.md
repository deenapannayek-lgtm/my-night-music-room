# My Night — Music Room

A cozy music room with a shared, searchable audio library and night-to-dawn ambience.

**[Open the live music room](https://deenapannayek-lgtm.github.io/my-night-music-room/)** · **[Find music](https://deenapannayek-lgtm.github.io/my-night-music-room/library.html)**

## Features

- Play tracks published in the shared library, available to every visitor
- Add local audio files for your own browser session
- Play, pause, skip tracks, and seek through the current track
- Adjust volume and browse the current playlist
- Switch the scene between night and dawn
- Search the shared library and open other song titles on Spotify or Apple Music
- Responsive layout for desktop and mobile

Tracks listed in `music/tracks.json` are loaded by the player and directory for every visitor. Local files selected in the player stay in that visitor's browser. To publish a track, add an audio file under `music/` and add an entry to `music/tracks.json` with `title`, optional `artist`, and `src` (for example, `music/song.mp3`). Only publish audio you have permission to distribute. The other song titles link out to Spotify and Apple Music.

## Run locally

Open `index.html` in a modern browser, or serve the repository with any static web server. There is no build step or dependency installation.

## Built with

HTML, CSS, and vanilla JavaScript. Hosted with GitHub Pages.
