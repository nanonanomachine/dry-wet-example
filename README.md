# Dry/Wet Mixer

A web-based audio mixer that allows you to blend between dry and wet audio signals in real-time.

## Features

- Real-time audio mixing between dry and wet signals
- Simple and intuitive user interface
- Web Audio API integration
- Responsive design
- No external dependencies

## Getting Started

1. Clone this repository
2. Add your audio files:
   - Place your dry audio file as `dry.mp3`
   - Place your wet audio file as `wet.mp3`
3. Open `index.html` in a modern web browser
4. Click the Play button to start
5. Use the slider to adjust the dry/wet mix ratio

## Usage

The mixer provides a simple interface with:
- A Play/Stop button to control audio playback
- A slider to adjust the dry/wet mix ratio (0.0 to 1.0)
  - 0.0 = 100% wet signal
  - 1.0 = 100% dry signal

## Technical Details

The application uses the Web Audio API to:
- Load and decode audio files
- Create separate gain nodes for dry and wet signals
- Mix the signals in real-time
- Handle audio playback and stopping

## Browser Support

This application works in modern browsers that support the Web Audio API, including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available under the MIT License.