#!/usr/bin/env osascript
# Returns the current playing song in Spotify for OSX

tell application "Spotify"
  if it is running then
    if player state is playing then
      set track_name to name of current track
      set artist_name to artist of current track

      artist_name & " - " & track_name
    end if
  end if
end tell
