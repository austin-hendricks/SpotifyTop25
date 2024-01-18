# SpotifyTop25

Simple idea to create a Spotify playlist automatically based on listening data.

Interfaces with Spotify's public API and OAuth flow to log into user account and perform actions. Logged-in dashboard displays session token, allows manual token refresh, and allows logout.

Main functionality is button that generates a playlist of the logged-in user's top 25 tracks from the past four weeks, and automatically adds the playlist to the user's Spotify library.

## Setup

After the following steps are complete, you should be all set to run this web app on your local machine.

1. [Register a Spotify App](https://developer.spotify.com/dashboard/applications) and add `http://localhost:5500/callback` (or your own live server's port number) as a Redirect URI in the app settings.

2. Copy the Client ID into `script.js` variable "clientId" at the top of the file.

3. In the same file, copy your Spotify username into the "username" variable.

4. Finally, in the same file, copy your redirect URL into the redirectUrl variable.
