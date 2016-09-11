# CANKinectPhysics
Kinect user tracking, blob detection and physics interaction in Processing. <br />
http://www.creativeapplications.net/processing/kinect-physics-tutorial-for-processing/<br />
Updated for Shiffman's Open Kinect library and Processing 3 <br />
OpenNI kinect library no longer works in Processing 3.x versions. OpenKinect lacks user body tracking with sceneImage() and userImage() functions of openNI, so this version of Amnon Owed original sketch uses depthImage data to make a threshold to separate user image from non-user to light and dark pixels. Tested with Kinext for xbox 360 model 1473 only.
