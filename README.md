# YT_DL_AUDIO - AHK
extract audio from browsers yt with AHK

requires youtube-dl https://github.com/ytdl-org/youtube-dl
Requires FFMPEG
Included 7zip archive with both yt-dl and FFMPEG (dont overwrite the youtube-dl.exe with the onefrom the 7zip)


optional config for specifying output folder:
  run _ config move.bat
  if not the output will be with the AHK

YT_DL_AUDIO.ahk:
  CTRL + WIN + X to extract audio of current 
i have managed to get it working in the background now.
ctrl shift + right arrow to skip to next video and Left arrow to previous

Bugs:
only works on the first tab on each chrome or firefox tab.
