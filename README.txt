###################################################################################
ENPM661 Project 3: A Star Algorithm Implementation
Aneesh Chodisetty (UID 117359893) and Bhargav Kumar Soothram (117041088)
###################################################################################

Instructions to run the code:

Download the package into a folder and cd into the location where the package is placed.

Run the code using the following command from the terminal:
python bsoothra.py -s {starting node} -g {goal node} -z {step size} -c {clearance} -r {robot radius} -sp {save path}
EXAMPLE COMMAND: python bsoothra.py -s 10,10,0 -g 200,180,0, -z 10 -c 5 -r 10 -sp "home/folder"

Output is saved as "project3.avi" in the current directory by default.


Dependencies: Numpy, OpenCV, time, copy, queue, sys, argparse, itertools, threading