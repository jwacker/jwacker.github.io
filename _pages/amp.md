---
layout: archive
title: "Stereo Amplifier"
permalink: /projects/amp/
author_profile: true
---


For one of my classes, I made a stereo amplifier to power a set of my speakers. The project simply had a potentiometer used as voltage control, a band pass filter from 100Hz to 15kHz, and a unity buffer to separate the two circuits...

## Band Pass
Firstly, the Band Pass filter. This is two passive high pass and low pass filters combined with a non-inverting op amp with a gain on 20 to meet the requirements of the project.
Potentiometers were used in the resistances of the two filters due to the wildly inaccurate capacitors. This allowed for exact and quick adjustment of the circuit.
The output of the Bandpass is fed directly into the speaker. The input comes from Voltage control passed through a Unity Buffer.

<iframe src="/images/amp1.png" width="520" height="292" style="border:none;"></iframe>

## Voltage Control

Voltage control is simply done with a potentiometer voltage divider. This allows control of the current to the Unity Buffer.

<iframe src="/images/amp2.png" width="520" height="292" style="border:none;"></iframe>

## Unity Buffer
A unity buffer is used to separate the voltage control from the band pass so that the resistance values of the voltage control would not effect the corner frequencies of the band pass. This is just a simple non-inverting op amp with a gain of 1.

<iframe src="/images/amp3.png" width="520" height="292" style="border:none;"></iframe>

## Oscilloscope Captures

Here's some oscilloscope outputs of the input signal vs the output from the amplifier.

### Voltage Control Showcase
<iframe src="/images/amp4.png" width="520" height="292" style="border:none;"></iframe>
<iframe src="/images/amp5.png" width="520" height="292" style="border:none;"></iframe>

### Amplitude at 100Hz
<iframe src="/images/amp6.png" width="520" height="292" style="border:none;"></iframe>

### Amplitude at 6000Hz
<iframe src="/images/amp7.png" width="520" height="292" style="border:none;"></iframe>

### Amplitude at 15000Hz
<iframe src="/images/amp8.png" width="520" height="292" style="border:none;"></iframe>

### Frequency Response
<iframe src="/images/amp9.png" width="520" height="292" style="border:none;"></iframe>

This thing sounds sweet!