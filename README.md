**IMAGE RECOGNITION**

**Introduction:**

This code uses YOLO (You Only Look Once), an object detection algorithm, to count and label objects in a video. It uses the YOLO model (loaded from the 'yolov8n.pt' file) to make predictions on each frame of the input video, then draws bounding boxes around the detected objects and labels them with their corresponding class names. The code also counts the number of instances of each class in each frame and displays the count along with the corresponding class name in a rectangle at the top left corner of the video output. The processed video is saved to the output file 'output.mp4'. 

**Requirements:**
* OpenCV
* YOLO
* Numpy

**Output:**

![Screenshot 2024-08-01 142124](https://github.com/user-attachments/assets/eee87e2f-52c4-4d5a-bae7-f10b64f1073b)
