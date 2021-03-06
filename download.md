---
title:  'Downloads'
pagetitle: 'PianoBooster Downloads'
---

# Version 1.0.0 (latest stable)

The **PianoBooster** executables now includes a built-in sound generator called **FluidSynth**.
In order for this to work a General MIDI (GM) SoundFont is required.
Since this is quite a large file its not necessarily included with the executable.
See below for the recommend SoundFont.

### Windows:

There is now an installer/uninstaller for windows.
Just download and run this setup program which also includes the recommend SoundFont.

* [PianoBoosterInstall-SF-1.0.0.exe](https://github.com/pianobooster/PianoBooster/releases/download/v1.0.0/PianoBoosterInstall-SF-1.0.0.exe) -- 143Mb (with SoundFont)


### Mac OS:
Unfortunately executables built on one macOS version may not work on a different version and so you may need to try both of these builds:

* [PianoBooster-macos-10.15-1.0.0.dmg](https://github.com/pianobooster/PianoBooster/releases/download/v1.0.0/PianoBooster-macos-10.15-1.0.0.dmg) -- 12.8Mb built on 10.15 Catalina (SoundFont not included)
* [PianoBooster-macOS-1.0.0.dmg](https://github.com/pianobooster/PianoBooster/releases/download/v1.0.0/PianoBooster-macOS-1.0.0.dmg) -- 12.8Mb built on 10.11 El Capitan (SoundFont not included)

These mac versions does not include a General-MID sound font.
See below for the  [recommend SoundFont](#recommend-soundfont).



### Linux AppImage (64 bit):

* [PianoBooster-1.0.0-x86_64.AppImage](https://github.com/pianobooster/PianoBooster/releases/download/v1.0.0/PianoBooster-1.0.0-x86_64.AppImage) -- 8Mb (SoundFont not included

For Linux users there is now no need to compile from source instead just download the PianoBooster AppImage set the executable bit and then run the AppImage.
This version includes the built in Fluid Synth sound generator but does not include a sound font.
Please install the `fluid-soundfont-gm` Fluid (R3) General MIDI SoundFont (GM) package before running Piano Booster.

### Recommend SoundFont:

The recommend SoundFont is called **FluidR3_GM**.
Use the Piano Booster 'Setup/Midi Setup' menu option and then click on the FluidSynth tab and use the load button to install the SoundFont file.

* [FluidR3_GM.sf2](https://github.com/pianobooster/fluid-soundfont/releases/download/v3.1/FluidR3_GM.sf2) -- 142 MB General MIDI SoundFont.



### MD5 sums


```txt
79daccb587ef872a37762af472de7ecf  PianoBooster-1.0.0-x86_64.AppImage
13b4cff404073c38a40b1db4f9a64b56  PianoBoosterInstall-SF-1.0.0.exe
0013743e1e2b7ce665cd513735c430b8  PianoBooster-macos-10.15-1.0.0.dmg
0c42fa85cf39394c62f45937b56c32c8  PianoBooster-macOS-1.0.0.dmg
```


# What is new

* Piano Booster now includes the built-in Fluid Synth sound generator which is especially useful on Windows at this solves the problem with the Windows MS GM Wavetable Synthesizer that has an unacceptable delay.
* A new PianoBooster MIDI music course is included.
* Detects left and right hand piano parts if held in separate MIDI tracks.


# Requirements

### MIDI files

Piano Booster now comes with it's own MIDI music course called `Booster Music`.
The first time you run Piano Booster a music folder called `BoosterMusicBooks` is created in your Music folder on your PC.
The Booster Music course with the MIDI files and sheet music can also be downloaded here [BoosterMusicBooks.zip](download/BoosterMusicBooks.zip)

Also many other MIDI files that work with Piano Booster can be found by searching the web.

### MIDI keyboard

To play along with Piano Booster you need a MIDI Piano Keyboard.
To connect the MIDI keyboard open the Piano Booster MIDI setup menu and
then select the MIDI input interface for your keyboard.
(If you don't have a MIDI keyboard you can still try out PianoBooster using the PC keyboard, 'x' is
middle C -- but a MIDI piano is recommend).


# Previous releases

Previous release are available here:

* [https://github.com/pianobooster/PianoBooster/releases](https://github.com/pianobooster/PianoBooster/releases)
* [https://sourceforge.net/projects/pianobooster/files/pianobooster/](https://sourceforge.net/projects/pianobooster/files/pianobooster/)
