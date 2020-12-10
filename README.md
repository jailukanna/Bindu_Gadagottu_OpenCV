# Bindu_Gadagottu_OpenCV
Open CV
## Face Detection 
1.Considering our prerequisites, we will require an image, to begin with. Later we need to create a cascade classifier which will eventually give us the features of the face.
2.This step involves making use of OpenCV which will read the image and the features file. So at this point, there are NumPy arrays at the primary data points.
3.This final step involves displaying the image with the rectangular face box.
<p>we create a CascadeClassifier object to extract the features of the face.The path to the XML file which contains the face features is the parameter here</p>
<p>The next step would be to read an image with a face on it and convert it into a black and white image using COLOR_BGR2GREY.  Followed by this, we search for the coordinates for the image. This is done using detectMultiScale.</p>
