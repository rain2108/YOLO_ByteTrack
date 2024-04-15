# YOLO_ByteTrack
## This program does the counting of the vehicles from the source video using YOLOv8 detection and Tracking vehicles using ByteTrack 

### Steps

1. Clone the repository:

    ```bash
    https://github.com/rain2108/YOLO_ByteTrack.git
    ```

2. Install dependencies:

    ```bash
    pip install ultralytics
    pip install supervision
    ```

3. Run the app:

    ```bash
    python main.py --source_weights_path <yolo_weights> --source_video_path <video_path> --target_video_path <result_path> --confidence_threshold 0.1
    ```
