# Non-Contact River Flow Measurement using OpenCV and Raspberry Pi

## Description

This project implements a non-contact river flow measurement system using computer vision techniques with OpenCV on a Raspberry Pi. The system captures video footage of the river's surface, processes the images to track flow patterns, and calculates the river's discharge rate.

## Features

- Non-contact river flow measurement using a Raspberry Pi and camera module.
- Real-time video feed for monitoring river flow.
- Image processing algorithms to detect and track flow patterns.
- Calculation of discharge rate based on flow patterns.

## Setup and Installation

1. **Hardware Setup:**
   - Connect the Raspberry Pi camera module to the Raspberry Pi.
   - Ensure the Raspberry Pi is connected to a stable power source.

2. **Software Installation:**
   - Install the required dependencies by running `pip install opencv-python` on your Raspberry Pi.
   - Clone this repository to your Raspberry Pi using `git clone https://github.com/Simran211103/flow-measurement.git`.

3. **Configuration:**
   - Adjust camera placement for optimal view of the river's surface.
   - Configure any parameters related to image processing and flow calculation in the code (if applicable).

4. **Running the System:**
   - Navigate to the project directory and run `python main.py` to start the flow measurement system.
   - Access the live video feed and measurement data through a web browser by entering the Raspberry Pi's IP address.

## Usage

1. Monitor flow patterns: Observe the river's surface through the video feed to monitor flow patterns and changes.

2. Calculate discharge rate: The system processes the captured images to calculate the river's discharge rate based on flow patterns.

## Contributing

Contributions to this project are welcome. Feel free to open issues or pull requests for bug fixes, improvements, or new features.


## Acknowledgements

- This project was inspired by the need for accurate and non-intrusive river flow measurement.
- We acknowledge the use of the OpenCV library for computer vision tasks.
- Special thanks to the Raspberry Pi community for providing affordable and versatile hardware.

## Contact

For questions or inquiries, please contact [chetiwalsimran579@gmail.com](mailto:chetiwalsimran579@gmail.com).
