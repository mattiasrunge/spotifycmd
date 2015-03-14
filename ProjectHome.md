# Introduction #

spotify\_cmd is a tool to control a running instance of Spotify under wine, it should work on Windows as well but have not been tested.


# Compile #

> wineg++ spotify\_cmd.cpp -o spotify\_cmd.exe

You should now have a Linux executable file named spotify\_cmd.exe

# Usage #

> _Play/pause playback_ **./spotify\_cmd.exe playpause**

> _Stop playback_ **./spotify\_cmd.exe stop**

> _Next track_ **./spotify\_cmd.exe next**

> _Previous track_ **./spotify\_cmd.exe prev**

> _Mute_ **./spotify\_cmd.exe mute**

> _Volume down_ **./spotify\_cmd.exe voldown**

> _Volume up_ **./spotify\_cmd.exe volup**

> _Artist and track information_ **./spotify\_cmd.exe status**

**Do NOT run as "_wine spotify\_cmd.exe_" it will not work, spotify\_cmd.exe is a Linux binary.**