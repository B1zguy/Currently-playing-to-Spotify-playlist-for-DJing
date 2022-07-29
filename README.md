# Currently-playing-to-Spotify-playlist-for-DJing
 
I was experimenting with ways to streamline adding songs to my DJing playlists (in Spotify). Currently switch to Spotify window to click through the menu when I want to add the playing song to several playlists - this esp painful on mobile. 

This script intended to be set of scripts deployed as shortcut (eg. via Better Touch Tools). Thus, can quickly add playing track to different playlists without leaving current window.

This rough implementation utilises the scripting support of Spotify Mac before engaging the Spotify API.  It's only role is to pull the currently playing song's (Spotify) ID which I later realised could be pulled from the Spotify API - my later goal is draft a mobile implementation which can't use Applescript. This, along with the hardcoded - for now - playlist is pumped into the curl API call to add to a playlist. 
I later realised this could probably be all done 'within' the Spotify API because it allows tracking current played (no matter device, and intended to go mobile later).