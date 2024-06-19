# MIPAC_microProject
Web Player project

Overview
This project is a customizable Web Player for HTTP Live Streaming (HLS) using the hls.js JavaScript library. The player supports predefined playlists, manual bitrate switching, and displays basic video information. Additionally, it tracks and displays all URLs requested by the player.

High-Level Requirements
Must Have
HLS Playback: The player allows for successful playback of HLS streams.
Predefined Playlists: Includes a dropdown menu with 2-3 predefined HLS playlists.
Manual Bitrate Switch: Provides buttons for manual switching between different bitrates.
Video Information: Displays bitrate, height, width, and video/audio codecs information.
Nice to Have
URL Tracking: Displays all URLs being requested by the player in real-time.
GEO-Based Control: Implements IP-based whitelisting or blacklisting to control access to premium content.
Files in the Project
index.html

HTML structure for the player interface.
Contains elements for video playback, playlist selection, bitrate buttons, video information, and URL logs.
styles.css

CSS styles for the player, ensuring a cohesive dark blue theme for the UI elements.
player.js

JavaScript logic for loading and controlling HLS streams using the hls.js library.
Handles manual bitrate switching, displaying video information, and logging requested URLs.
