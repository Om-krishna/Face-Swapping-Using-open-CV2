# Face-Swapping-Using-open-CV2
This is a basic face-swap implementation using OpenCV. Check out the code for a step-by-step explanation.

# Requirements
1) OpenCV v3.0+
2) numpy
3) dlib (for the landmark detection)
4) Python 3

# Abstract
Face swapping has been a thriving genre of work which primarily is associated with the replacement or substitution of one referral face on the face of 
the other person, be it by means of still images or in real time. This paper exhibits our research on the Real-Time Face Swapping algorithm, using the reference image of the user and henceforth considering it as our input image instead of using a dataset and working on a live model. The input image facial features and attributes are extracted and are replaced to make the final resulting output through our model. We start by training our model to learn the facial alignments and features to be able to recognize a face and extract its features before swapping it. Now, we head over to the process of image warping by the dissociation and partitioning of the user’s face and its background. To increase the precision of the model, in the second part of parsing the face is performed to cancel out other features of the live image, hence our output is obtained. In our research, we have tried to bring accuracy and precision to our model by improving the condition of the image, editing out borders, and training it to a bunch of data for face recognition and   correction. Our analysis delivers the most subtle outputs alongside performing the tasks with the process including the analysis of our image and its output too. We deliver our model to improve the conditions of security, privacy, image capture, and entertainment purposes.
