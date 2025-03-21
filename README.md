# DistorLineal - Audio Plugin

**DistorLineal** is a Projucer-based audio plugin developed using **JUCE** that combines linear distortion and an **IIR (Infinite Impulse Response)** filter, designed to be used in **Ableton Live** (or any other VST-compatible DAW). This plugin allows users to add rich distortion effects to their audio while utilizing a customizable IIR filter for precision sound shaping.

## Features
- **Linear Distortion**: Adds harmonic distortion to the input signal, perfect for enhancing sound and adding warmth or grit to your audio.
- **IIR Filter**: Provides precise frequency response shaping with minimal phase shift, allowing for advanced sound design.
- **Low CPU Usage**: Designed with optimization in mind to ensure smooth performance, even with complex projects.
- **Easy Integration**: Fully compatible with DAWs supporting VST plugins, including Ableton Live.

## What I Learned
- **C++ for Audio Processing Applications**: Deepened my understanding of using C++ for real-time audio processing and effects.
- **JUCE DSP Implementation**: Gained experience in implementing **digital signal processing (DSP)** algorithms using JUCE, focusing on distortion and filter effects.
- **Plugin Development**: Learned the process of building, debugging, and optimizing an audio plugin, ensuring it performs well across different platforms and DAWs.
  
## Installation

To install and use the **DistorLineal** plugin:

1. Build the project from source using **Projucer** (JUCE's project management tool).
2. Place the generated VST plugin file in your DAW's plugin directory.
3. Launch your DAW (e.g., Ableton Live) and scan for new plugins.
4. Load **DistorLineal** onto your track or effect chain.

## Usage

Once loaded into your DAW, you can adjust the following parameters:

- **Distortion Amount**: Controls the level of distortion applied to the input signal.
- **Filter Frequency**: Sets the cutoff frequency for the IIR filter.
- **Filter Resonance**: Adjusts the resonance of the filter to shape the tone.

## Technical Details
- **Built with JUCE**: The plugin was developed using the **JUCE framework**, a widely used C++ library for building audio applications.
- **IIR Filter**: Implemented using optimized algorithms to ensure minimal CPU usage and high-quality sound processing.
- **Distortion Effect**: Linear distortion was applied using custom code to create a harmonic effect that adds warmth and edge to the sound.

## Contribution

Feel free to fork the repository, open issues, or contribute to the development of the **DistorLineal** plugin. Pull requests and feedback are always welcome!