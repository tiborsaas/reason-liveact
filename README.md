# Reason live setup
This project enables you to play live-acts in Propellerheads Reason. I created this project, because it's not really obvious how to create live shows with Reason. It can be great if you play in a band and use it as an instrument, but when you need to mix between 10 tracks and build up, tweak each track, then it becomes ticky to set everything up correctly.

# Requirements
 * A MIDI controller with at least 8 knobs or faders
 * Some time to convert your tracks to combinators
 * Reason 8 is ideal, because it's easier to switch focus of combinators, but any Reason version is good that supports Rack Extensions

# Features
 * Forward CV messages to the currently selected combinator
 * Two channel output
 * Select on each combinator which channel to route the audio
 * Select on each combinator which group of MIDI knobs to listen to
 * Turn REX loops on/off in each combinator and keep them playing tempo synced by sending MIDI notes

# Usage
Main idea is to use the combinators as individual tracks. Send MIDI notes from C1 to D#2 and toggle loops on and off. By default the combinator has 4 loops included. The Kong's upper 8 slots are directly triggered, this is handy for individual sample triggering.

You can chose which output to send each combinator: A or B. In a main mixer, you can adjust levels and crossfade between them, like a DJ mixer. Alternatively, you can just route the Audio mergers to the hardware interface and use an analougue mixer.

# Required Rack Extensions
 * A/B Audio & CV Switch (Free, [download](https://shop.propellerheads.se/product/ab-audio-cv-switch/))
 * Blamsoft Polymodular Audio merger (Free, [download](https://shop.propellerheads.se/product/polymodular-audio-merger/))
 * Blamsoft Polymodular CV splitter (Free, [download](https://shop.propellerheads.se/product/polymodular-cv-splitter/))
 * Morfin XF Crossfader (Free, [download](https://shop.propellerheads.se/product/morfin-xf-crossfader/))
 * CV8x4 CV Generator (Free, [download](https://shop.propellerheads.se/product/cv8x4-cv-generator/))

`Please note` You don't need the Alias8 hardware, any device MIDI is good with knobs / faders.
