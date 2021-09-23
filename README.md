# birds-eye-vision
by using the **_Perspective Transformation_** function from **_OpenCV_** show the bird's-eye vision.</br>
## What is Perspective Transformation?
As clear from the name, the perspective transformation is associated with the change in the viewpoint. This type of transformation does not preserve parallelism, length, and angle. But they do preserve collinearity and incidence. This means that the straight lines will remain straight even after the transformation.</br>
</br>Since the transformation matrix (M) is defined by 8 constants(degree of freedom), thus to find this matrix we first select 4 points in the input image and map these 4 points to the desired locations in the unknown output image according to the use-case (This way we will have 8 equations and 8 unknowns and that can be easily solved).</br></br>
Once the transformation matrix is calculated, then we apply the perspective transformation to the entire input image to get the final transformed image. 
</br></br>
In this code, you can see how to apply birds-eye view on an image and videos too by the Perspective Transformation function 
## NOTE
I attached the image that I used **_"highway.jpg"_** and the video too **_"road.mp4"_** you can find a video of the run too **_"video of the run.mp4"_** and there is a **_"requirements.txt"_** do not forget it
