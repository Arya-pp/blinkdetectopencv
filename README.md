# blinkdetectopencv 
This project helps you to find the eye blink rate of a video , be it a live one direct from your webcam  or  a demo video already in your disk.
## Team members
1. CLERINE MARIA IGNATIOUS [https://github.com/CLERINE-MARIA-IGNATIOUS]
2. ARYA PP [https://github.com/Arya-pp]
3. SHIFA BHASHEER 
4. DRISHYAMOL M [https://github.com/Drishyamol]
## Team Number
12
## Link to product walkthrough
Here's a demonstration of our work : https://www.loom.com/share/afba63beb10247d7b84a6af1e9b7ad9c
## How it Works ?
In this project we use opencv to analyse the input video to find  the eye aspect ratio(EAR).Blink is registered when the EAR falls below a certain threshold and then rises above the threshold. The EAR threshold is 0.3 in this case.The blink count is determined this way.
## Libraries used

imutils : 0.5.4

dlib : 19.22.99

cv2 (opencv-python) : 4.6.0.66

## How to configure
Install python, preferably version 3.10 and all the libraries mentioned above.<br />
Now, clone the repo and run it.
## How to Run

For the blink rate of an input video , give this  command in the terminal :<br />
python blinkeye.py --shape-predictor shape_predictor_68_face_landmarks.dat --video "link" <br />
The video should be within the same folder where all the codes lie and the link of the same should replace the “link” in the above command 

For the blink rate of a live video from the webcam , uncomment the  commented lines 51 and 52 <br />
"vs = VideoStream(src=0).start()" <br />
"fileStream = False" <br />
Give this  command in the terminal :<br />
python blinkeye.py --shape-predictor shape_predictor_68_face_landmarks.dat