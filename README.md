# SkyStream - Bluesky Hashtag Tracker

[SkyStream](https://skystream.nothans.com/) is a simple, elegant web application that allows you to track and display posts from Bluesky containing specific hashtags.

## Features

- 🔍 Search for any Bluesky hashtag
- 🔄 Auto-refreshes every 30 seconds
- 📱 Responsive design
- 🎨 Material Design interface
- 🔀 Two display modes:
  - Classic view with avatar and formatted text
  - Embedded Bluesky posts with native interaction

## Usage

1. Enter your desired hashtag in the search field (default: #CheerLights)
2. Set the number of posts you want to display (1-100)
3. Toggle between classic and embedded post views
4. Click "Update Stream" to refresh manually, or wait for auto-refresh

## Technical Details

The application uses:
- Bluesky's public API endpoint (`app.bsky.feed.searchPosts`)
- Material Design Lite for UI components
- Native JavaScript (no framework dependencies)
- Bluesky's official embed script for embedded post view

## API Reference

The app uses the following Bluesky endpoint: 
```
https://public.api.bsky.app/xrpc/app.bsky.feed.searchPosts
```
    
