---
title:  'Frequently Asked Questions'
pagetitle: 'PianoBooster FAQ'
---

## Where are the music files?
**PianoBooster** now comes with it's own MIDI music course called `Booster Music`.
The first time you run Piano Booster a music folder called `BoosterMusicBooks` is created in your `Music` folder on your PC.
The Booster Music course is also available on the Piano Booster website.
Also many other MIDI files that work with Piano Booster can be found by searching the web.

## There is no sound, what is wrong?
First insure that you have installed the latest version of Piano Booster that includes the integrated FluidSynth sound generator. To check this open the Piano Booster MIDI setup dialogue window and confirm there is a FluidSynth tab shown. You also need to ensure that there is a SoundFont file loaded, the recommended sound font is called `FluidR3_GM.sf2`.

## How do I connect a MIDI piano keyboard?
First plug the MIDI keyboard into your PC, for older MIDI keyboards that do not use USB MIDI you will need to use a MIDI adaptor.
After connecting the MIDI keyboard open the Piano Booster MIDI setup menu and
then select the MIDI input interface that matches your keyboard.

## Will Piano Booster work with a real piano?
No, it will only work with a MIDI piano keyboard.
As this is technically very difficult there are no plans to add this feature.
A MIDI keyboard is recommended and then you can transfer your skills back to the real piano.


## Does Piano Booster work with JACK?
JACK is not required for Piano Booster to work correctly since Piano Booster can already talk directly to a MIDI sound generator and a MIDI keyboard.
JACK is mainly used in advanced music studio setups where there are multiple different sound sources inputs and outputs that need connecting together.
JACK is also required on BSD Unix. Piano Booster is not normally compiled with support for JACK so if you really want to use JACK you will need to recompile Piano Booster from the source code.


## How do I start start a sound generator on Linux?
If you don't have a version of Piano Booster that includes the integrated FluidSynth (recommended) you can start FluidSynth manually. First install the FluidSynth `fluidsynth` and the GM sound font `fluid-soundfont-gm` packages and then run the following command line:

```txt
fluidsynth -g 1.0 -a alsa -o midi.alsa_seq.id=fs2 /usr/share/sounds/sf2/FluidR3_GM.sf2

```
An alternatively you can used TiMidity by typing the following in a terminal window:

```txt
timidity -iA -B2,8 -Os -EFreverb=0
```

## What is the latency fix?
The latency fix is no longer required since Piano Booster on Windows now includes the integrated FluidSynth sound generator which works in real-time and has low latency.
Previously on windows the latency fix was required when using the MS GM Wavetable Synthesizer sound generator which has very high latency.
