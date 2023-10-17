# README ALE

## Intro (abstract from work)

Equalization is a crucial tool contributing to high audio quality for playback loudspeakers in their
acoustic environment. In our work, we implement filters that automatically calculate its coefficients
to flatten the loudspeaker’s magnitude over an averaged listening area. Different spectral resolutions
and filter designs are evaluated by using the prototype implementation. The parallel filters impress
with the very low latency and consistent spectral discretization. The minimum-phase finite impulse
response (FIR) filter benefits from an even better resolution at high frequencies; the higher latency
does not enable real-time applications. Similar to the FIR filter, the main disadvantages of linear-
phase FIR filters are high latency and lower linear frequency resolution. Due to its symmetry, an
unwanted pre-ringing effect can also occur. An acoustical measurement of an example loudspeaker in
a room verifies the functionality of the designed filters.


## Contents


*   [Getting started](#getting-started)
    *   [Requirements](#requirements)
    *   [Install](#install)
    *   [Usage](#usage)
*   [Contribute](#contribute)
*   [License](#license)


## Getting Started

Download the "ALEv3.mlapp" and run it or download the binary file, which should run if you have installed Matlab on your computer.
Please leave a comment if it's not working, everything was compiled on a Mac so there might be some issues with windows or linux idk tbh.
Created with Matlab / Matlab Appdesigner R2022b.

### Requirements

* computer with Matlab 
* audio Interface for maesurments
* measurement microphone with mic correction curve (.txt)
* loudspeakers to measure ;-)

### Install

Use git to clone this repository into your computer.

```
git clone https://github.com/simonwindtner/ALE
```

### Usage
We added a sample mic correction curve "Reference.txt" as well as an Multi-IR "IRs_A7x_R_3x5pos.mat" in order to play around with the app. 
Further you can read the whole documentation which is provided in the pdf.


## License
[MIT](https://choosealicense.com/licenses/mit/)

