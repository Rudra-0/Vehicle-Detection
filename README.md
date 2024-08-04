# Vehicle-Detection
Vehicle Detection

# Vehicle Detection in Video using YOLOv5

This project demonstrates vehicle detection in a video using the YOLOv5 model from the Ultralytics repository. The script processes each frame of a video to detect vehicles and save the annotated frames into a new video file.

## Requirements

- Python 3.6+
- PyTorch
- OpenCV
- YOLOv5

## Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/vehicle-detection-yolov5.git
    cd vehicle-detection-yolov5
    ```

2. **Install the required packages**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare the input video**

    Place your input video in the `test_vids` directory and ensure it is named `test_1.mp4` or modify the script to point to your specific video file.

2. **Run the detection script**

    ```bash
    python yolo_mdl.py
    ```

    This will process the input video and create an output video named `output_video.mp4` with detected vehicles annotated.

## Notes

- The script displays the processed frames in a window. Press `q` to quit the video display.
- Ensure your environment has internet access to download the YOLOv5 model the first time you run the script.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
