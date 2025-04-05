MIDI-Interactive Heart Visualization
Overview
This project creates an interactive, MIDI-driven heart visualization using p5.js. The heart's properties such as position, size, color, transparency, and rotation are controlled via MIDI input, providing a dynamic, user-driven experience. Additionally, the background color changes based on MIDI pads, and the heart's size is dynamically adjusted using sound spectrum analysis, responding to bass and mid frequencies of the audio track.

Features
MIDI Controller Support:

Knobs control the heart's position, size, color (RGB), transparency, and rotation.

Pads trigger changes in the background color.

Sound Spectrum Visualization:

The heart’s size dynamically adjusts based on the bass and mid frequencies of the audio being played.

Play/Pause Button: Allows you to control the song playback.

Heart Shape Visualization: A heart shape is drawn and manipulated based on user input and the song's sound.

Installation


Usage
MIDI Pads: Press any of the pads to change the background color.

MIDI Knobs: Use the knobs to control the heart's properties:

Position (X, Y)

Size

Color (Red, Green, Blue)

Transparency (Alpha)

Rotation

Audio: Play your own MP3 file by replacing mysong.mp3 in the preload() function.

Dependencies
p5.js (JavaScript library)

Web MIDI API for MIDI device communication.
