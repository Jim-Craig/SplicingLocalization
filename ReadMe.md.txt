Image splicing Detection using CNN:
In this project, we'd want to find teh portion of the images that have been tamperd with. 
Every jpeg image has a compression factor that is uniform across the image, But if a image has been tampered with then the the compression ratio changes and this particular case of splicing, we'd get a portion of teh image(that has been tampered with) that has a compression ratio different form the rest of the image.

We'd have a CNN model that takes in the image and generated the outputs the regions that it predicts to have been tampered with
