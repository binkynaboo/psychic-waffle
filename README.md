# Audio Emotion Visualizer

Transform your music into a visual emotional experience. This web-based visualizer converts .wav audio files into dynamic dot patterns that reflect the emotional qualities of the music through movement, size, and color.


## Features

- **Audio Visualization**: Upload any .wav file and see it transformed into moving dots that represent the emotion of the music
- **Highly Customizable**: Adjust dots size, density, color, brightness, contrast, and more
- **Background Controls**: Customize the background with color, brightness, and contrast settings
- **Real-time Response**: Dots react instantly to the music's emotional qualities
- **Video Export**: Record and download videos with synchronized audio for sharing
- **Resolution Options**: Support for multiple aspect ratios and resolutions
- **Adaptive Experience**: Works on both desktop and mobile devices

## How It Works

The visualizer analyzes your audio in real-time across three key frequency ranges:
- **Bass frequencies**: Control dot intensity and size
- **Mid-range frequencies**: Determine movement complexity
- **High frequencies**: Affect brightness and visual energy

This creates a unique visual representation of each song's emotional qualities.

## Usage

1. Open the visualizer in your web browser
2. Upload a .wav audio file
3. Adjust the dot and background settings to your preference
4. Use the play/pause button to control the visualization
5. Record your visualization by clicking "Start Recording"
6. Download the video (includes audio) for sharing

## Customization Options

### Basic Controls
- **Dot Size**: Adjust the base size of each dot
- **Dot Density**: Change the number of dots in the visualization
- **Sensitivity**: Control how responsive the dots are to audio input

### Advanced Controls
- **Background/Dot Color**: Choose custom colors
- **Brightness/Contrast**: Fine-tune the visual appearance
- **Curve Setting**: Adjust the non-linear response to audio intensity

## Technical Details

This visualizer is built with pure HTML, CSS, and JavaScript. It uses:
- Web Audio API for sound analysis
- HTML5 Canvas for visualization
- MediaRecorder API for video capture

No external dependencies or libraries required.

## Setup

Simply download the HTML file and open it in any modern browser. No installation, server, or build process needed.

## License

[MIT License](LICENSE)

## Acknowledgements

Created with passion for music visualization. Feel free to fork, improve, and share!

---

If you use this visualizer for a project, I'd love to see what you create! Tag me or submit a pull request with examples.
