# echo on noteoff

![image of echo of noteoff Max for Live device](img/eono.gif)

## What is this?
An experimental Max for Live MIDI effect designed for notes in arpeggios.
Put before built-in Arpeggiator to acquire decaying effects in arpeggio notes!

## Download 
https://maxforlive.com/library/device/5563/echo-on-noteoff

## Requirements
- Ableton Live 11.1 / Cycling '74 Max 8.2 or later

## Parameters
(ordered in the appearance of the automation control chooser list)
- `Delay mode` (Sync/Free) Switches whether delay offset of echo notes to the song tempo or calibrate it in milliseconds.
- `Delay` (free/sync) Adjusts the delay offset time to start echo notes.
- `Duration mode` (Sync/Free) Switches whether the duration of echo notes to the song tempo or calibrate it in milliseconds.
- `Duration` (free/sync) Adjusts the duration time to start echo notes.
- `Feedback` Adjusts the ratio for the velocity of feedback echo notes.
- `Velocity` Adjusts the ratio for the velocity of the first echo note from note off.
- `Reset` Stop and disable all notes. Pressing the button always makes an undo history of Live.
- `Auto Stop` With it on, the device work as the specialized mode for use with Arpeggiator.
Echo notes are always stopped by receiving new notes, and actual note offs and the start of echo notes are suspended until all playing notes were off.

## Known Issues
see [Issues](https://github.com/h1data/M4L-echo-on-noteoff/issues?q=)
