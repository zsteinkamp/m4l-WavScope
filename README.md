# WavScope

This is a Max For Live device that displays audio as a waveform with an adjustable "zoom" control.

![How it Looks](images/device.gif)

This is useful to see how an effect changes the waveform if you put a WavScope before an and after the effect. With its Sidechain control, you can visualize two waveforms at once. This is useful for balancing kick and bass, among other things.

I made a [video going through building a simpler version of this device step-by-step](https://www.youtube.com/watch?v=bW8M0wRehgE). Maybe do that instead of just downloading it?

## Installation

Download the newest .amxd file from the [Releases Page](https://github.com/zsteinkamp/m4l-WavScope/releases) or clone this repository, and drag the `WavScope.amxd` device into a track in Ableton Live.

## Changelog

* 2025-09-24 [v4](https://github.com/zsteinkamp/m4l-WavScope/releases/download/v4/WavScope-v4.amxd) - Adds Sidechain input and second visualizer.
* 2024-11-02 [v3](https://github.com/zsteinkamp/m4l-WavScope/releases/download/v3/WavScope-v3.amxd) - Split/Join mode, vertical scaling, more compact.
* 2024-10-29 [v2](https://github.com/zsteinkamp/m4l-WavScope/releases/download/v2/WavScope-v2.amxd) - Adds non-blocking, non-identifying telemetry.
* 2024-10-18 [v1](https://github.com/zsteinkamp/m4l-WavScope/releases/download/v1/WavScope-v1.amxd) - Initial release.

## Usage

Place in a track to see the audio activity at that point.

Use the `Time` control to zoom in or out of the waveform, stepped in note increments.

Use the `Link` control to synchronize the Time control with other instances of this device that also have `Link` enabled.

Use the `Scale` control to zoom vertically (does not change the audio volume, only the waveform display).

Toggle between Split and Join view with the `Split / Join` button.

Use the `Sidechain` controls to display a second waveform. Useful to help balance kick and bass, as [shown here](https://www.youtube.com/watch?v=DfHf97U4-Fk).

## TODO

* ...

## Contributing

I'd love it if others extended this device. If you would like to contribute, simply fork this repo, make your changes, and open a pull request and I'll have a look.
