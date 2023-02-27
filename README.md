# Head-pose-estimation-using-ML-

## **DISCOVER YOUR PROBLEM FIRST**

Since the face of a person can rotate over all three axis — but with some limitations, of course.  **We want to detect theses movments Using ML MODEL**. We call these movements the Euler Angles (Roll, Pitch, and Yaw)..

![EULAR](https://user-images.githubusercontent.com/84232181/221378945-98cf5323-cb2c-42ea-9c60-e93c6c2a3f7d.png)

### Why Machine Learning :

In normal cases, we can solve the head pose problem mathmatically if we have **3D landmarks** (check yhis article)[https://medium.com/analytics-vidhya/real-time-head-pose-estimation-with-opencv-and-dlib-e8dc10d62078, but in our problem we have only **2D landmarks** so the mathmatical solution is fired here.>> check these sources

            -1:(Face Alignment Across Large Poses: A 3D Solution||paper)[https://arxiv.org/pdf/1511.07212.pdf] 
            
            -2:(Head Pose Estimation with Computer Vision||blog)[https://indatalabs.com/blog/head-pose-estimation-with-cv]
You need the 2D (x,y) locations of face landmarks. I used two approches 
1: using the points which determine the face ( the tip of the nose, the chin, the left corner of the left eye, the right corner of the right eye, the left corner of the mouth, and the right corner of the mouth).
2: using all face landmarks which extracted by mediapie, they are 465 points.

First approch didn't work well but second one gave me high accuray.

![6_points](https://user-images.githubusercontent.com/84232181/221610477-68369696-01f4-49d4-b30b-7f33778fb060.png) ![facial-landmarks-python-points](https://user-images.githubusercontent.com/84232181/221379667-1e208b4b-8cf5-4bd9-80e4-de02d9d1c56f.jpg)   

            
##  How to get theses 2D landmarks 


## Steps:

# 1:



