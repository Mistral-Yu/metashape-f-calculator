# Metashape f Calculator

A small single-page calculator for estimating Metashape camera calibration `f` and pixel size from focal length, sensor size, and image resolution.

[Open the calculator on GitHub Pages](https://mistral-yu.github.io/metashape-f-calculator/)

## Features

- Computes Metashape `f` in pixels
- Shows diagonal pixel size and Pixel X / Y
- Shows a RealityScan-style full-frame long-edge equivalent focal length
- Loads editable presets from `presets.json`
- Supports output-only 16:9 video shortcuts for 8K, 4K, and FHD
- Runs as a dependency-free static page

## Formula

```text
pixel_size = sensor_size / image_size
f = focal_length / pixel_size
```

The visible Metashape reference links to Agisoft's official camera model documentation.

## Usage

Open `index.html` locally, or use the GitHub Pages link above.
Edit `presets.json` to change the default preset list. Added presets can be exported as JSON and pasted back into that file.

## License

MIT
