# Nova Music Architecture

## Purpose
Nova Music is organized around a browser-first interface for discovering, selecting, and playing music.

## UI responsibilities
- Keep playback controls independent from page navigation.
- Keep the active track visible while browsing the library.
- Prefer semantic buttons and labels for keyboard and screen-reader support.

## State responsibilities
Playback state should have a single source of truth for the current track, play/pause state, volume, and progress. UI components should react to state changes instead of duplicating playback logic.

## Extension points
Future features such as playlists, favorites, queue management, and keyboard media controls should be added without coupling them directly to presentation markup.
