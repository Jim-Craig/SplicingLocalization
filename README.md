Image splicing Detection using CNN:
In this project, we'd want to find teh portion of the images that have been tamperd with. 
Every jpeg image has a compression factor that is uniform across the image, But if a image has been tampered with then the the compression ratio changes and this particular case of splicing, we'd get a portion of teh image(that has been tampered with) that has a
compression ratio different form the rest of the image.

We'd have a CNN model that takes in the image and generated the outputs the regions that it predicts to have been tampered with. The model being used here is made on top of an image segmentation model called InceptionV3. We preproces the images input using the resnet 

Sample Image 

![image](https://github.com/user-attachments/assets/4de15d57-8551-4c86-b1d4-4f53d4bea28d)


Result of the model

![image](https://github.com/user-attachments/assets/c719af97-60c5-4264-9ff5-3158dd5c2578)

