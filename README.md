# Face-Detection-Using-the-DLIB-Face-Detector-Model

n this article, we will be discussing the face detection process using the Dlib HOG detection algorithm. Though in this article we will not only test the frontal face but also different angles of the image and see where our model will perform well and where not along with that we will be computing the total time taken by the HOG detector model to detect the faces in the image.

Application of Face Detection
Security purpose: Face recognition is turning out to be the most common method to maintain the security of the individual/organization.
Ride-sharing companies: It will help them to check whether the right person was picked by the driver or not.
Home automation: To maintain security, especially in a home that is driven by technology face detection and recognition is essential.

Dlib HoG Face Detection
If we want to know about the HOG face detection then first let’s break down the term which is the Histogram of oriented gradients which is not only a face detection algorithm but also a complete object detection method in general. HOG is basically a feature descriptor that is performed both for image processing and computer vision techniques.

HOG uses mainly 5 filters during the preprocessing step they are as follows:

Frontal face
Right side turned face
Left side turned face
The frontal face but rotated right
The frontal face but rotated left

Loading the HOG Face Detector
We have by far understood what is HOG face detector but to use it we have to first load the face detector i.e. dlib.get_frontal_face_detector() function which is a pre-trained method and this function has the dlib library beforehand so we don’t even need to include the main model file.
