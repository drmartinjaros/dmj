dmj is a library for Pure Data running in a Windows 64-bit machine, by Martin Jaroszewicz with five sections: control, experimental,
filters, gui, and signal. 

 - data objects: atan2 banger elliptic euclid gamepad martbox midicc ritmo unique wintablet
 
 - objects for controlling filters: biquad2~

 - GUI objects: fader hdial image knob led

 - signal objects: binaural~ compressor~ convolution~ fmsynth~ granular~ pwm~ waves~ waveshaper~

## Overview
DMJ is a Pure Data (Pd) library designed specifically for Windows 64-bit systems.

## Requirements
- Pure Data (Pd)
- Windows 64-bit operating system

## Installation

1. Download and run the installer from the repository.

2. The library will typically install in the standard Pure Data externals folder:
   - Path: `C:\Users\%USERNAME%\Documents\Pd\externals`

3. Installation Location
   - If you choose a different installation directory, manually add the library path in Pure Data preferences:
     * Open Pure Data
     * Go to `Preferences` > `Path`
     * Click `Add` and select the folder containing the DMJ library

4. Verification
   - Restart Pure Data after installation
   - Check that the library objects are available in your patches

## Troubleshooting
- Ensure you have the correct Pure Data version
- Verify Windows 64-bit compatibility
- Restart Pure Data if objects are not immediately recognized


## Contributing
Contact me


## Description of dmj Pure Data Externals

**[atan2]** The atan2() function returns the angle theta in radians from the conversion of rectangular coordinates (x, y) to polar coordinates (r, theta).

**[banger]** Limited bangs at a rate.

**[binaural~]** Algorithmic binaural panner (azimuth, elevation, and distance).

**[biquad2~]** Biquadratic filter with graph output.

**[compressor~]** Classic dynamic range compressor with ratio, threshold, attack, release, knee, and make-up gain.

**[convolution~]** Convolution of two signals with a Hanning window.

**[elliptic]** Elliptical trajectories.

**[euclid]** Euclidean rhythm generation. This object generates Euclidean trigger patterns, resulting in onsets in the rhythm to be as equidistant as possible.

**[fader]**† Simple vertical slider.

**[fmsynth~]** Frequency modulation with cosine table of 16384 points.

**[gamepad]** Receives data from a game controller.

**[granular~]** Real time granular engine.

**[hdial]**† Vu meter dial.

**[image]**† An (png) image loader that can behave as a button.

**[knob]**† A simple knob.

**[led]**† A simple led and pow4. 

**[martbox]** This object reads all the analog pins from an Arduino.

**[midicc]** Receives MIDI control messages in a given range.

**[pwm~]** Anti-aliased pulse-width-modulation square wave.

**[ritmo]** Rhythmic sequences with abstract notation.

**[router]** work in progress, passthrough for now, for routing organization.

**[unique]** A unique machine id (Windows).

**[waves~]** Interpolation between sine->triangle->square->sawtooth waves. (aliased)

**[waveshaper~]** Waveshaping functions: (t)anh, (a)tan, (p)oly, (e)xponential, (s)igmoid.

**[wintablet]** A Wacom tablet object for Windows.

 **†** GUI objects.

Dr. Martin Jaroszewicz



