# Optical Flow and Motion Tracking

Academic computer vision project developed using Python and OpenCV.

The application processes video streams and visualizes movement using dense and sparse optical flow methods.

## Implemented Modes

### Mode 1 – Dense Optical Flow with HSV Visualization

Movement direction is represented by hue, while motion magnitude is represented by brightness.

### Mode 2 – Dense Optical Flow with Motion Vectors

Motion is visualized using lines and points drawn over the original video frame.

### Mode 3 – Lucas-Kanade Optical Flow

Selected feature points are tracked between frames using the Lucas-Kanade method. The application also calculates and displays inferred motion vectors.

## Additional Functionality

- Camera and video-file input
- Image cropping and resizing
- Horizontal image flipping
- Frame capture
- Processed MP4 video export
- Interactive switching between visualization modes

## Technologies

- Python
- OpenCV
- NumPy
- Click
- Dense optical flow
- Lucas-Kanade optical flow

## Controls

- `1` – Dense optical flow with HSV visualization
- `2` – Dense optical flow with vector visualization
- `3` – Lucas-Kanade optical flow
- `S` – Save the current frame
- `F` – Flip the image horizontally
- `Space` – Pause or resume
- `Esc` – Exit

## Project Status

Academic prototype. The repository demonstrates practical work with video processing, motion analysis and computer vision algorithms.
