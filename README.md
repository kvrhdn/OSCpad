# OSCpad
SuperCollider script to control the Novation Launchpad via OSC.

Made by [@koenaad](https://twitter.com/koenaad).

## Usage
To start OSCpad, simply execute the first block of commands (starting at line 1). OSCpad will dump which port it listens on. This is typically `57120`, but might sometimes switch to `57121`.

To restart the script (resetting the list of subscribers, connecting to the Launchpad again), simply execute the block again; all listeners will be cleaned up before being installed again.

To stop the script, euh... reboot the interpreter or quit SuperCollider.

The API is described at the top of the file.

The bottom of the file has some commands to listen to the OSC output or send test OSC or MIDI data.

## What is this
I made this script to hook up the Novation Launchpad Mini to Unity3d. It was a fun experience getting to know OSC, SuperCollider and Unity better. I thought it might be useful for someone else.

Since OSC is a network protocol you could technically connect to a Launchpad on a different computer. Might be cool.