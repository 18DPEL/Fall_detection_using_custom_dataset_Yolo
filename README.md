# Fall_detection_using_custom_dataset_Yolo

This repository contains a Python script for object tracking using the YOLO (You Only Look Once) deep learning model. The script utilizes the ultralytics library to load the YOLO model and perform object tracking on a video file.

# Installation
Clone the repository to your local machine.
Install the required libraries by running pip install -r requirements.txt.
# Usage
i will provide the link for custom model in requirement.text file you can download from 
Download the YOLO weights file (best.pt) and place it in the root directory of the project.
Update the video_path variable in the script with the path to the video file you want to perform object tracking on.
Run the script to start the object tracking process.
Press the 'q' key to exit the tracking process.
# Customization
Model: You can use different YOLO models by replacing the best.pt file with other YOLO weights files.
Frame Size: Adjust the frame size in the cv2.resize function to change the size of the displayed frames.
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
