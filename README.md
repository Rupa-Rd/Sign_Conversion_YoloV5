# Sign Language Detector
This project aims to develop a real-time sign language detection and translation system that bridges the communication gap between the hearing-impaired community and the general public. The system will utilize computer vision and machine learning techniques to recognize and interpret sign language gestures, converting them into words.
## Steps to detect
1. Clone the Repository
2. Create a virtual environment
3. Activate the virtual environment
4. Install the requirements
5. Excute the program



### Clone the repository
<strong>Clone the current repository by following the steps given below:</strong> <br>
1. Click Code -> Local -> Https -> Copy to clipboard <br>
<img src="Screenshots/S1.png">
<br>
2. Go to you local machine -> Open VS Code <br>
3. Open Terminal
<img src="Screenshots/S3.png"><br>
<br>
4. Paste the command <br>
`git clone https://github.com/Rupa-Rd/Sign_Conversion_YoloV5.git`
5. Check whether all the files present in the repository got cloned into your local machine
<img src="Screenshots/S4.png">

### Create a Virtual Environment
In the Terminal type<br>
`python -m venv sign`<br>
This will create a python virtual environment named `sign`
<img src="Screenshots/S5.png">


### Activate the Virtual Environment
In the terminal type <br>
`sign\Scripts\activate` <br>
<img src="Screenshots/S6.png">


### Install the Requirements
After activating the virtual environment, install the requirements<br>
`cd yolov5`  <br>
`pip install -r requirements.txt`
<img src="Screenshots/S7.png">

### Excute the Program
This command will execute the real-time sign language detection <br>
`python run.py`
<img src="Screenshots/S8.png">

## Output
<img src = "YOLO_v5\runs\train\exp6\val_batch0_labels.jpg">