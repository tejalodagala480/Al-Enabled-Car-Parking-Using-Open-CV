# Al-Enabled-Car-Parking-Using-Open-CV
AI-Enabled Car Parking Is A System That Uses Computer Vision To Monitor Parking Spots And Detect Vacant Spaces.

Al Enabled Car Parking Using Open CV

Car parking is a common problem faced by drivers in busy urban areas. For example, imagine you are driving to a shopping mall during peak hours. As you approach the mall, you notice that the parking lot is full, and several other cars are circling around looking for available spots.
You join the queue of cars, hoping to find an available spot soon. However, as time passes, you realize that the parking lot is overcrowded, and it's becoming increasingly difficult to find a spot. You start to feel frustrated and anxious, knowing that you might be late for your appointment or miss out on a great shopping opportunity.
AI-enabled car parking using OpenCV is a computer vision-based project that aims to automate the parking process. The project involves developing an intelligent system that can identify empty parking spaces and gives the count of available parking spots.
The system uses a camera and OpenCV (Open-Source Computer Vision) library to capture live video footage of the parking lot.

# Architecture:

![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/12f74376-2a68-4226-beba-7ac850a546b1)

Videos were recorded using a camera that was ten feet above the parking lot. To ameliorate the system's ability to recognise objects, video footage was collected under various environmental and temporal situations. Frames are used to segment video. also, to reduce computational complexity, a key frame is uprooted from each segment and subjected to additional processing. Key frame subtraction is used to estimate the motion of the toy auto when it enters or exits the parking lot from the parking arena. 
At first, there were no parking lanes in the parking lot. The user must manually enter the location of the intended parking spot and the car. The system automatically creates virtual parking spaces while taking the size of the vehicle into consideration. In our training model, the number of parking spaces is limited to fourteen. Each parking lot has a different numeric label, ranging from 1- 4. 
Our system will check to see if there are any cars in each block after the parking area has been partitioned into virtual blocks. 
Inverse binary is used to take out the car as the area of past time ROI after applying a binary filter to the image. Calculating the connected region's value in ROI and designating a parking space as reserved when the threshold value exceeds eighty. The count of unreserved sections will be displayed to drivers in green, while the number of reserved sections will be displayed in red.

![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/18e5f8a4-74d9-40c9-9d79-c8950c6af97d)

# Labelling of a detection position is initial step. Labelled scenes include:
![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/853223fe-677b-4d64-9a75-b711d25553a2)


# Al-Enabled-Car-Parking-Using-Open-CV
- This project find outs the count of empty and occioped parking spaces in a car-parking-lot using through digital image processing techniques form opencv.

- Clone the repository.
```
git clone https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV
```
- Goto the cloned folder.
```
cd Al-Enabled-Car-Parking-Using-Open-CV

```
- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```
- Run the code with mentioned command below.

`app.py`

 
## Example Results


<p align="center">
<img src="data/results/example_result.png">


## Problem Defination
- finding out the empty parking spaces in a Al-Enabled-Car-Parking-Using-Open-CV automatically from servillance camera.

## solution
- Extracting the parking lot coordinates form the image by car_park_coordinate_generator.py script.
- Then use this coordinates to processing every car parking space individualy.
- Implementing digital iamge processing techniques to find out the empty and occupied parking spaces.
- drawing the reults into the image. 

## Used The Concepts
- OOP concepts
- Opencv High Level GUI Programming
- Opencv Basic Image Processing
- Doc String
- Python Type Annotation



### Controlling with the project
- labelling   __car park__
    - you can click left  mouse button. It will draw the its order.
- removing the label __car park__
    - you will do same thing above with mouse middle button instead of clicking left mouse button.

- __Exit__ from the project
    - just click __q__ button on your keyboard. (When your Operating System Selected the project window)
- __Saving__ the results
    - just click __s__ button on your keyboard. (When your Operating System Selected the project window)


## Note 
- CarParkingPos  is a pickle file which stores the empty car parking positions.  The car park areas represented as rectangle and they stored with coordinate of  its top left point.
