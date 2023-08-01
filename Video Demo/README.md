# Al Enabled Car Parking Using Open CV

Car parking is a common problem faced by drivers in busy urban areas. For example, imagine you are driving to a shopping mall during peak hours. As you approach the mall, you notice that the parking lot is full, and several other cars are circling around looking for available spots.
You join the queue of cars, hoping to find an available spot soon. However, as time passes, you realize that the parking lot is overcrowded, and it's becoming increasingly difficult to find a spot. You start to feel frustrated and anxious, knowing that you might be late for your appointment or miss out on a great shopping opportunity.
AI-enabled car parking using OpenCV is a computer vision-based project that aims to automate the parking process. The project involves developing an intelligent system that can identify empty parking spaces and gives the count of available parking spots.
The system uses a camera and OpenCV (Open-Source Computer Vision) library to capture live video footage of the parking lot.

# Architecture:
![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/3c51ca75-3e56-428b-af0f-3a6e48875082)

# DESIGN AND IMPLEMENTATION

The primary route-way of the proposed algorithm for parking space discovery are. 
1. The parking lot will be live- streamed by the camera to the system. 
2. When a horseless carriage pulls into or out of the parking space, filmmaking are taken. 
3. Grayscale images are created by converting RGB images. 
4. Make a adjustments Choosing the parking lot's equals first is a good idea. This will remove any unnecessary white space from the image other than the parking lot. 


• Next, decide where the single parking space's parallels are. As a result, the parking lot will be divided into spaces of cognate size. 
5. In order to turn the parking lot into black and the auto into white, each block is first converted from grayscale to double and then to inverse binary. 
6.To determine if a block contains a car or not, a threshold value is computed for each block. Blocks are free and available for parking if their value is less than a threshold value, and they're occupied if their worth exceeds the threshold.

 ![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/9dedf894-b32a-4df5-bec8-f9ee3a7e54e9)

# Pre-Requisites
1.	To complete this project, you must have the following software versions and packages. 
To make a responsive Python script you must require the following packages. 

•	PyCharm (Download: https://www.jetbrains.com/pycharm/ ) 


•	Python 3.7.0 (Download: https://www.python.org/downloads/release/python-370/ )


•	NumPy


•	Cv zone

Flask: 

•	Web framework used for building web applications. 

•	Flask Basics: Click here 

If you are using anaconda navigator, follow the below steps to download the required packages: 
•	Open anaconda prompt. 

•	Type "pip install OpenCV-python” and click enter. 

•	Type "pip install cv zone” and click enter. 

•	Type “pip install Flask” and click enter. 

If you are using PyCharm IDE, you can install the packages through the command prompt and follow the same syntax as above.


# Project Flow

•	Data Collection
o	Download the dataset.

•	ROI (Region of interest)
o	Create python file.
o	Import required libraries.
o	Define ROI width and height.
o	Select and deselect ROI.
o	Denote ROI with BBOX

•	Video Processing and object detection
o	Import required libraries.
o	Reading input and loading the ROI file
o	Checking for parking space
o	Looping the video
o	Frame processing and empty parking slot counters

•	IBM Database Connection
o	Create IBM DB2 service and table.

•	Application building
o	Build HTML
o	Build Python script for Flask.

# Download The Dataset
Click the below link to download the dataset for AI-Enabled Car Parking using OpenCV. 
Link - https://drive.google.com/drive/folders/13vNq4XZLV15uxxXrVkj33Jr7VflrhKWr?usp=share_link

# Video Processing and Object Detection
Create a new Python file to perform video processing, object detection, and counters.

# Application Building
In this section, we will be building a web application that is integrated to the model we built. A UI is provided for the uses where he must enter the values for predictions. The enter values are given to the saved model and prediction is showcased on the UI.
This section has the following tasks.

•	Building HTML Pages 

•	Building python code

# Building Html Pages
•	For this project, we have created 2 HTML files and saved them in the templates folder. Let’s see what those HTML pages looks like:



