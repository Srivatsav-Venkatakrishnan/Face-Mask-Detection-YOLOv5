# Face Mask Detection-YOLOv5
The system is designed to accurately detect and classify the presence or absence of face masks in live video feeds or images, enabling rapid response in health-sensitive environments. Leveraging the power of YOLOv5, this solution provides a balance between speed and accuracy, making it suitable for deployment in real-world applications.

## Real-Time Face Mask Detection using YOLOv5

This repository contains the implementation of a real-time face mask detection system using the YOLOv5 model. The system is designed to detect and identify face masks in live video feeds or static images, providing a powerful tool for enhancing safety in various environments.

## Dataset

Here's the link to the dataset - [Insert your dataset link here]

| **Database**            | **Image** | **With Mask** | **Without Mask** |
|-------------------------|-----------|---------------|------------------|
| Face_Mask_Detection      | 853      | 800           | 53               |

## Features

- **Real-Time Processing**: Efficiently processes video streams with minimal delay.
- **High Accuracy**: Leverages the YOLOv5 model for precise face mask detection.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- Required Python libraries (specified in `requirements.txt`)

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Face-Mask-Detection-YOLOv5.git
   cd face-mask-detection-YOLOv5
   
2. **Install Dependencies:**
pip install -r requirements.txt

4. **Prepare Your Model:**
Ensure that your YOLOv5 model weights are downloaded and that the .xml and .bin files are in place.

4. **Usage:**
To run weapon detection on a video, use the following command:
cd D:\Mini_project\face-mask-yolov5-master\deployment
python app.py --host localhost:3000 --weights=D:/Mini_project/face-mask-yolov5-master/deployment/models/weights/yolov5s.pt

5. **Result Viewing:**
   After running the code to check the result, Open chrome and paste the below site.
   http://localhost:3000/
   
 6. **Model and Weights:**
The model used for detection is based on YOLOv5s, Ensure the weights file is correctly linked in the commands above.

To use the model in real time on your local environment download the model weights zip file and change the model weights path in test.py code and run to get the final output video.

7. **Result/Output:**

  To check the results open the results file which is uploaded above in the repository.
   

9. **License**
This project is licensed under the MIT License. See the LICENSE file for details.

   


