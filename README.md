Spotifox

* Spotify player that uses spotify web to play songs
* Display song title from cli
* Can alternate title between mpd and spotify depending on what's playing

INSTALLATION
* Clone this repo <br/>
  ```
  git clone https://github.com/SreeHarshan/Spotifox/ && cd Spotifox
  ```
* Create a separate profile called spotify in firefox <br/>
  ```
  firefox -CreateProfile spotify
  ```
* Make the spotify file executable <br/>
  ```
  chmod +x spotifox
  ```
* Copy the file into user executables dir <br/>
  ```
  sudo cp spotifox /usr/bin/spotifox
  ```
* Copy the desktop entry <br/>
  ```
  sudo cp spotifox.desktop /usr/share/applications/spotifox.desktop
  ```

NOTE
* This uses firefox profile to play spotify on separate web browser
* Make sure to create a profile called "spotify" on firefox

Future works
* Make an install script
* Build a polybar custom module 
* Mute ads on spotify and play a song on mpd
