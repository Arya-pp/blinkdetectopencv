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
This project helps you to find the eye blink rate of a video , be it a live one direct from your webcam  or  a demo video already in your disk.
## Libraries used

imutils : 0.5.4

dlib : 19.22.99

cv2 (opencv-python) : 4.6.0.66

## How to configure
Install python 3.0 preferably for all the libraries mentioned above.
## How to Run

>>For the blink rate of an input video , give this  command in the terminal :\n
python blinkeye.py --shape-predictor shape_predictor_68_face_landmarks.dat --video "link" \n
the video should be within the same folder where all the codes lie and the link of the same should replace the “link” in the above command 

>>For the blink rate of live video from the webcam , uncomment the  commented lines 51 and 52\n
"vs = VideoStream(src=0).start()" \n
"fileStream = False" \n
Give this  command in the terminal :\n
python blinkeye.py --shape-predictor shape_predictor_68_face_landmarks.dat