# plex-compose
Plex and plex related applications - Docker-compose


# Stream
  This is utilized for an endpoint to have a local repository sync in your home for best streaming capabilities.
  Will need to remove preferences.xml from plex config location if copying another server, then utilize ssh tunnel to server, then hit 127.0.0.1:32400 and configure server to be 
  online. Will also need to edit autoscan config to make sure api is set up properly, and docker name is set up properly. 
