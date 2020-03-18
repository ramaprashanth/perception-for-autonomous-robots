# Traffic Sign Recognition
We aim to do Traffic Sign Recognition with the two steps of detection and recognition. We use existing OpenCV code (HOG feature detector, MSER feature detector, SVM routines) to createthe complete pipeline.  The challenge is tune the system to detect well.

Traffic Sign Recognition can be staged into two sections: Traffic Sign Detection and Traffic Sign Classification.In the Detection stage we aim to extract possible candidates (or regions) which contain a traffic sign (in this part, we do not care what the sign might be).  In the Classification stage, we go over each Region of Interest(RoI) extracted previously and try to identify a traffic sign (which might not be in that RoI at all).

## DataSet Download
The dataset can be downloaded from here : 
https://drive.google.com/open?id=0B8DbLKogb5ktTW5UeWd1ZUxibDA

Place the `TSR` in the same folder as the code.

## How to run code
1. Unzip the folder which has the code, input images.
2. Copy the TSR images folder such that the *.py files are in the same directory level.
3. Run `denoising.py` to prepare the images.
4. Each of the following code parts needs to be separately run.
5. For Traffic Sign Recognition proposed pipeline run
        `python3 MSER_main.py`

## Results
https://drive.google.com/open?id=1ISggFDhmIMsEAYzBQnjLNut-d9nOjzPL

  <p align="center">
  <img src="https://github.com/ramaprashanth/perception-for-autonomous-robots/blob/master/Traffic%20Sign%20Recognition/result_1.png">
  </p>

  <p align="center">
  <img src="https://github.com/ramaprashanth/perception-for-autonomous-robots/blob/master/Traffic%20Sign%20Recognition/result_2.png">
  </p>

  <p align="center">
  <img src="https://github.com/ramaprashanth/perception-for-autonomous-robots/blob/master/Traffic%20Sign%20Recognition/result_3.png">
  </p>
