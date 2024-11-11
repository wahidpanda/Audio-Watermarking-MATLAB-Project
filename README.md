# Audio-Watermarking-MATLAB-Project
Watermark Audio and Image GUI is a MATLAB-based graphical user interface that allows users to apply watermarks to audio files using image data. 


# Watermark Audio and Image GUI

This is a MATLAB GUI application that allows users to upload an audio file and an image, apply a watermark to the audio using the image data, and then visualize and play both the original and watermarked audio. The app also provides functionalities to display the grayscale version of the image and its histogram.

## Features

- **Upload Audio**: Upload an audio file (WAV format) and visualize its waveform.
- **Upload Image**: Upload an image file (PNG, JPG, JPEG, BMP, GIF) and visualize the grayscale version and its histogram.
- **Watermark Strength (WMS)**: Adjust the watermark strength using a slider.
- **Play Original Audio**: Play the original audio.
- **Play Watermarked Audio**: Play the audio after watermarking.
- **Apply Watermark**: Apply watermarking to the audio using the grayscale image and visualize the modified audio waveform.
- **Grayscale Plot**: View a line plot of the grayscale version of the image.
- **Histogram**: View the histogram of the grayscale image.

## Requirements

- MATLAB 2019b or higher
- Audio and Image Processing Toolbox (for audio and image manipulation)

## Installation

1. Download the project files to your local machine.
2. Open the MATLAB application.
3. Navigate to the directory where the project is stored using the MATLAB command window.
4. Open the GUI application by typing `gui` in the command window.

## Usage

1. **Upload Audio**: Click the "Upload Audio" button to upload a WAV audio file.
2. **Upload Image**: Click the "Upload Image" button to upload an image (supports PNG, JPG, JPEG, BMP, and GIF formats).
3. **Adjust Watermark Strength**: Use the slider to adjust the watermark strength. The slider value ranges from 0 to 100.
4. **Play Audio**: Use the "Play Original Audio" and "Play Watermark Audio" buttons to play the respective audio.
5. **Apply Watermark**: Click the "Apply Watermark" button to apply the watermark to the audio using the image and the chosen watermark strength.

## Screenshots

![Screenshot of GUI](./assets/gui_screenshot.png)

## File Structure

- `gui.mlapp`: The main MATLAB app file containing the GUI and its logic.
- `assets/`: A folder containing any additional resources like images or icons (optional).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- MATLAB for providing the powerful platform to create this GUI.
- The MATLAB documentation for helping with the functions used in this project.

## Contact

For any issues or contributions, feel free to reach out or create a pull request.
