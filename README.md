🧠 Age and Gender Detection using OpenCV
This project uses OpenCV's Deep Neural Network (DNN) module and pre-trained Caffe models to detect age group and gender from webcam or video input.

📁 Project Files
File Name	Description
gender_age.py	Main Python script to run detection
age_deploy.prototxt	Age model architecture
age_net.caffemodel	Age model weights
gender_deploy.prototxt	Gender model architecture
gender_net.caffemodel	Gender model weights
opencv_face_detector.pbtxt	Face detection model config
opencv_face_detector_uint8.pb	Face detection model weights

⚙️ Requirements
Install dependencies using pip:

bash
Copy
Edit
pip install opencv-python
🚀 How to Run
▶️ To run with webcam:
bash
Copy
Edit
python gender_age.py
📹 To run with image or video input:
bash
Copy
Edit
python gender_age.py -i path_to_video_or_image
💾 Download Model Files
All the required model files are hosted on Google Drive.

🔗 Google Drive – Download Models

⚠️ Important:
The files are not publicly accessible.
If you want to download the files, you must click "Request Access" on the Google Drive link.
Access will be granted manually.

🎯 Labels Used
Age Groups: (0-5), (6-25), (26-50), (51-75), (76-100)

Genders: Male, Female

🖼️ Output Features
The system detects faces in real time.

It predicts age group and gender, then displays them on screen.

Press S to save an image with detected results.

