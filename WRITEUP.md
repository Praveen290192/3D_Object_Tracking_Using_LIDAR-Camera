### FP.1
Identifying same object in 2 different consecutive images.
### FP.2
Computing TTC Lidar by using constant velocity model
### FP.3
Filtering noise of matches from previous and current matches by calculating average distance between keypoints and removing keypoints those are outside averange 
### FP.4
Computing TTC by using camera images.
### FP.5
1. Some of the lidar data that we are processing are from the curvature of the vehicle, due to which our mean is been shifted further away from lidar. This might cause wrong measurements of the TTC.
2. We haven't input any velocity of the vehicle, assuming vehicle are travelling with constant velocity. This might also be reason for fluctuation of TTC.
<img src="TTC LIDAR.png" width="779" height="414" />
<img src="TTC Lidar, red TTC, blue distance, yellow speed.png" width="779" height="414" />

### FP.6
Using different detector and descriptor best results were obtain AKAZE detector with FREAK/BRISK/ORB/BRIEF descriptor does provide more accurate results with decent matches but needs more computation time.
<img src="TTC Camera using AKAZE detector.png" width="779" height="414" />