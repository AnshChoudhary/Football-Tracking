# Football Analysis System with Machine Learning and Computer Vision

![Output Video](path/to/your/gif.gif)

This repository contains a football analysis system that leverages machine learning, computer vision, and deep learning techniques to analyze football matches. The system utilizes state-of-the-art object detection models, custom object detectors, pixel segmentation, optical flow, perspective transformation, and speed-distance measurement to provide comprehensive insights into player movements and match dynamics.

## Features

1. **Object Detection with YOLOv8**: Utilizes Ultralytics and YOLOv8 to detect players, referees, and footballs in images and videos.

2. **Custom Object Detection**: Fine-tunes and trains a custom YOLO model on a dataset tailored specifically for football analysis, enhancing object detection accuracy.

3. **Pixel Segmentation with KMeans**: Employs KMeans clustering to segment players from the background based on the colors of their t-shirts, providing accurate player identification.

4. **Optical Flow for Camera Movement**: Implements optical flow techniques to measure camera movement between frames, ensuring precise analysis of player movements.

5. **Perspective Transformation**: Utilizes OpenCV's perspective transformation to represent the scene's depth and perspective, enabling measurements of player movement in meters rather than pixels.

6. **Speed and Distance Measurement**: Calculates players' speed and distance covered in the image, offering valuable insights into player performance.

## Getting Started

To get started with using the football analysis system, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/AnshChoudhary/Football-Tracking.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the provided scripts or integrate the system into your own project as needed.

## Usage

The system provides various scripts and modules for different tasks:

- `yolo_inference.py`: Perform object detection using YOLOv8.
- `football_training_yolo_v5.ipynb`: Fine-tune and train a custom YOLO model.
- `team_assigner.py`: Segment players from the background using KMeans.
- `camera_movement_estimator.py`: Measure camera movement using optical flow.
- `view_transformer.py`: Apply perspective transformation to represent scene depth.
- `speed_and_distance_estimator.py`: Calculate player speed and distance covered.

You can use these scripts individually or combine them to achieve specific analysis tasks.

## Contribution

Contributions to this project are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Ultralytics for providing the YOLOv8 implementation.
- OpenCV for the powerful computer vision functionalities.
- Contributors to various libraries and frameworks used in this project.
