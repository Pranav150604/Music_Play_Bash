# Music Player Bash Script
This Bash script provides a simple music player interface using Zenity dialogs and the mpv media player. It allows users to play audio files, pause, resume, stop, skip tracks, and adjust volume, all within a graphical interface.

## Prerequisites
Zenity: Zenity is a program that allows for easy creation of graphical user interfaces (GUIs) for Bash scripts.<br> Install it using your package manager if not already installed.

mpv: mpv is a multimedia player for playing audio and video files. Ensure it is installed on your system.
<br>You can install it using your package manager:

sudo apt install mpv    # For Debian/Ubuntu
sudo yum install mpv    # For CentOS/RHEL
## Usage
Running the Script:
Execute the script using Bash:
bash music_player.sh<br>
<br>
Main Menu:
The main menu presents options to Play, Pause, Resume, Stop, Skip Track, Adjust Volume, or Quit the music player.
Choose an option by clicking on it.<br>

Playing Audio:
Click "Play" to select an audio file using the file selection dialog.
The script will display song information including the song name, elapsed time, and remaining time.<br>

Pause, Resume, Stop, Skip Track:
Click "Pause" to pause the playback.<br>
Click "Resume" to resume playback.<br>
Click "Stop" to stop playback.<br>
Click "Skip Track" to skip to the next track in the playlist.<br>

Adjusting Volume:
Click "Adjust Volume" to set the volume level using the volume slider.<br>

Quit:
Click "Quit" to exit the music player.
## Notes
This script relies on mpv for audio playback. Ensure mpv is installed and accessible in your system's PATH.

The script uses Zenity dialogs for the graphical interface. Make sure Zenity is installed on your system.

You may need to adjust the paths and configurations in the script according to your system setup.
