# Social Media Profile Photo Helper
Machine Learning Project MET-CS767
The following tool helps us to select a good profile photo for our social media accounts. It works in the following steps:
1. Detects if the image has a face
2. Calulates a brisque score(lower than 15 is better) of the original image.
3. Uses pridictive GAN model to supersample the image and improve the brisque score.
4. We use our tensorflow model to detect a happy or sad face in the image.
