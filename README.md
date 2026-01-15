# mp3toRC5wav
Send a backtrack from url to your USB connected Looper Pedal (here Boss RC5)

# Requirements
## yt-dlp
https://github.com/yt-dlp/yt-dlp

## ffmpeg
https://www.ffmpeg.org/

# Usage

This is bash script. At the time of this writing, it is made to work out of the box with a Boss RC5, but adapting it for another pedal is only a matter of tweaking. A futur version version will allow to specify a pedal model in the command line or to specify one in a configuration file.

Usage: mp3toRC5wav [--url <URL>] [--save-to-rc5-first-free-slot | --save-to-slot X]

Example: mp3toRC5wav --save-to-rc5-first-free-slot <Youtube URL>
