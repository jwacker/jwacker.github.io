---
layout: archive
title: "Network Filter"
permalink: /projects/bandpass/
author_profile: true
---


For one of my classes, I made a single op amp circuit for a Cross Over Network. 

## Filters
This project required 3 filters :
* 200 Hz Low Pass with 1-5 Gain with 40 dB/decade roll off
* 300 – 5000 Hz Band Pass with 20 dB/decade roll off
* 6000 Hz High Pass with 40 dB/decade roll off

Here are some photos of the final circuit:
<iframe src="/images/filter1.png" width="520" height="292" style="border:none;"></iframe>
<iframe src="/images/filter2.png" width="520" height="292" style="border:none;"></iframe>

## Low Pass
The Low Pass filter is a simple design using only capacitors and resistors. Variable gain was done with the potentiometer. Below are the sketches of the curcuit, as well as the resulting frequency response chart.
<iframe src="/images/filter3.png" width="520" height="292" style="border:none;"></iframe>
<iframe src="/images/filter4.png" width="520" height="292" style="border:none;"></iframe>

## Band Pass
The Band Pass filter was done with another simple design using only capacitors and resistors. A unity gain buffer was used to join the two first order (passive) circuits togeather to create the band pass filter.
<iframe src="/images/filter5.png" width="520" height="292" style="border:none;"></iframe>
<iframe src="/images/filter6.png" width="520" height="292" style="border:none;"></iframe>

## High Pass
The High Pass filter was done with another simple design using only capacitors and resistors. This circuit was designed like the low pass filter, but with capacitor and resistors swapped to form a high pass filter.
<iframe src="/images/filter7.png" width="520" height="292" style="border:none;"></iframe>
<iframe src="/images/filter8.png" width="520" height="292" style="border:none;"></iframe>

## Conclusion

Our circuit preformed as designed, however, capacitors that we had used in our circuit were off by an error of 35% from their actual value, as mearsued by the lab equipment. This mean that resistors had to be swapped out to find values that would actually result in the correct frequency response we wanted.