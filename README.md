# ASCII Art Converter

## Overview

**ASCII Art Converter** is a minimalistic web-based tool that allows users to:
- Convert plain text into a simple ASCII representation.
- Upload an image and transform it into ASCII art.

It combines functionality with a retro-inspired design, simulating an old CRT terminal aesthetic. The tool is lightweight, responsive, and user-friendly.

## Features

- **Text to ASCII:** Instantly convert typed text into ASCII-styled output.
- **Image to ASCII:** Upload any image and generate its ASCII equivalent.
- **Copy to Clipboard:** Easily copy the generated ASCII art with a single click.
- **Clear Workspace:** Quickly reset the input and output areas.
- **Subtle Visual Effects:** Particle animations and slight glitch animations to enhance the retro aesthetic without interfering with functionality.

## Technologies Used

- **HTML5**
- **CSS3** (including custom animations)
- **Vanilla JavaScript**
- **Canvas API** (for image processing)
- **Google Fonts:** VT323 and Space Mono

## How to Use

1. **Enter Text:**
   - Type any text into the provided textarea.
   - Click the "Convert Text" button to display the text in the ASCII output area.

2. **Upload Image:**
   - Click on "Upload Image" and select an image file from your device.
   - Click the "Convert Image" button to transform the image into ASCII art.

3. **Copy Result:**
   - Click on the "Copy" button located at the top right of the output container to copy the generated ASCII art to your clipboard.

4. **Clear Workspace:**
   - Click the "Clear" button to reset both input and output sections.

## Project Structure

- **HTML:** Defines the structure of the application.
- **CSS:** Styles the interface to mimic a retro terminal and adds glitch and particle effects.
- **JavaScript:** Handles input processing, ASCII generation, copy-to-clipboard functionality, particle effects, and basic image resizing.

## Notes

- **Image Size Limitation:**
  - Uploaded images are resized internally to a maximum width of 100 pixels to maintain performance and ensure readability of the ASCII output.
  - Aspect ratio is preserved.

- **ASCII Character Set:**
  - A graded set of characters (`[' ', '.', ':', '-', '=', '+', '*', '#', '%', '@']`) is used to represent different brightness levels from dark to light.

- **Performance:**
  - Optimized for fast processing of small to medium-sized images.
  - Not intended for high-resolution image conversion.

## Credits

- **Fonts:** [VT323](https://fonts.google.com/specimen/VT323), [Space Mono](https://fonts.google.com/specimen/Space+Mono)
- **Design and Development:** [Tirup Mehta](https://github.com/TirupMehta)

## License

This project is released under the MIT License.
