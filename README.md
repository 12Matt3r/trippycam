# Real-time Glitch Art & Datamosh Effects

This project is a single-page web application that applies real-time glitch art and datamosh effects to a webcam stream or uploaded media. It uses WebGL for rendering and provides various controls to adjust the visual effects.

## Features

- Real-time video effects using WebGL.
- Works with webcam input or uploaded image/video files.
- Multiple effect types: Datamosh, Pixel Sort, Feedback, Color Shift.
- Adjustable parameters for each effect, including:
    - Trailing
    - Motion detection
    - Hue shifting
    - Intensity
    - Displacement
    - Feedback amount
    - Threshold (for pixel sort)
    - Brightness, Contrast, Saturation
- Presets for quick effect setups (Default, Psychedelic, Ghostly, Neon Traces, Glitchy VHS, Dreamy).
- Frame freezing and clearing.
- Video recording and snapshot functionality.
- Controls panel with minimize and resize options.
- Responsive design with tabbed navigation for controls.
- Floating "Randomize Effects" button for quick experimentation.

## How to Use

1.  Open the `index.html` file in a web browser that supports WebGL.
2.  Allow webcam access if prompted, or use the "Upload" button to select an image or video file.
3.  The application will start applying effects to the video stream or selected media.
4.  Use the controls panel on the bottom left to:
    *   Select different **Presets** from the dropdown.
    *   Switch between **Main Controls**, **Effects**, and **Advanced** tabs to fine-tune parameters.
    *   Adjust sliders and number inputs for various effect properties like `Trailing`, `Motion`, `Hue`, `Intensity`, etc.
    *   **Freeze Frame**: Click to capture and hold the current frame. Multiple frozen frames can be captured.
    *   **Clear Frozen**: Clears all captured frozen frames.
    *   **Record Button** (circle/square icon): Start/stop recording the output. The video will be downloaded when stopped.
    *   **Snapshot Button** (camera icon): Take a still image of the current output.
    *   **Refresh Button** (circular arrows icon): Refresh the current media stream.
    *   **Switch Camera Button** (camera flip icon, mobile only): Switch between front and rear cameras.
    *   **Minimize/Maximize Controls**: Use the `_` or `+` button in the controls header.
    *   **Resize Controls**: Drag the bottom-right corner of the controls panel.
5.  Use the "Randomize Effects" button on the top right for a quick change of visual style.

## Technologies Used

-   HTML5
-   CSS3
-   JavaScript
-   WebGL (for real-time graphics rendering and effects)

## Contributing

Contributions are welcome! If you have ideas for new effects, improvements, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch for your feature or fix.
3.  Make your changes.
4.  Submit a pull request.

## License

This project is likely under an open-source license, but a specific `LICENSE` file is not present. Please add one if you intend to distribute this project.
