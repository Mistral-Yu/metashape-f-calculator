# Metashape f Calculator

A small single-page calculator for estimating Metashape camera calibration `f` and pixel size from focal length, sensor size, and image resolution.

[Open the calculator on GitHub Pages](https://mistral-yu.github.io/metashape-f-calculator/)

## Features

- Computes Metashape `f` in pixels
- Shows diagonal pixel size and Pixel X / Y
- Shows a RealityScan-style full-frame long-edge equivalent focal length
- Includes presets for a7R V, a6400, and a full-frame 1.6K square setup
- Runs as a dependency-free static `index.html`

## Formula

```text
pixel_size = sensor_size / image_size
f = focal_length / pixel_size
```

The visible Metashape reference links to Agisoft's official camera model documentation.

## Usage

Open `index.html` locally, or use the GitHub Pages link above.
