# Lucas-Kanade(LK) Template Tracking
We implement the Lucas-Kanade (LK) template tracker.  Then you will evaluate your codeon three video sequences from the Visual Tracker benchmark database:  featuring a car on the road, a humanwalking, and a box on a table.  The short video that you will process are available in this folder.

To  initialize  the  tracker  you  need  to  define  a  template  by  drawing  a  bounding  box  around  the  objectto  be  tracked  in  the  first  frame  of  the  video.   For  each  of  the  subsequent  frames  the  tracker  will  update  anaffine transform that warps the current frame so that the template in the first frame is aligned with the warpedcurrent frame.

We also look at ways to make tracking more robust, by incorporating steps to increaseillumination invariance.

## DataSet Download
The dataset can be downloaded from here : 
https://drive.google.com/open?id=1WiYKUU8pfAGo-UktzUKCQGugLmwNIShH

Place the `data` in the same folder as the code.

## How to run code
1. Unzip the folder which has the code, input sequences and the datasets.
2. Each of the following code parts needs to be separately run.
3. For lucas kanade tracking run
        `python3 part_1.py`

## Results
https://drive.google.com/open?id=1RBBSpxIfen3_MmVeiPm1XsP7TesmA4hd