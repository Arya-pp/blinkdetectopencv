# blinkdetectopencv
small description
## Team members
1. CLERINE MARIA IGNATIOUS [https://github.com/CLERINE-MARIA-IGNATIOUS]
2. ARYA PP [https://github.com/Arya-pp]
3. SHIFA BHASHEER
4. DRISHYAMOL M
## Team Number
12
## Link to product walkthrough
[link to video]
## How it Works ?
1. Explaining the working of project
2. Embed video of project demo
## Libraries used

imutils : 0.5.4

dlib : 19.22.99

cv2 (opencv-python) : 4.6.0.66

## How to configure
Instructions for setting up project
## How to Run
Install all the required apps and libraries

For the blink rate of an input video , give this  command in the terminal :

python blinkeye.py --shape-predictor shape_predictor_68_face_landmarks.dat --video "link"

the video should be within the same folder where all the codes lie and the link of the same should replace the “link” in the above command 

For the blink rate of live video from the webcam , uncomment the  commented lines 51 and 52

"vs = VideoStream(src=0).start()"

"fileStream = False"

Give this  command in the terminal :

python blinkeye.py --shape-predictor shape_predictor_68_face_landmarks.dat