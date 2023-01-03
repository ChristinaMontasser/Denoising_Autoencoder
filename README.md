# Denoising_Autoencoder

I have trained an autoencoder (with CNN layers) to encode and decode an image. The input image have noise, which was sampled from the normal distribution, added to itز  

Then I compare putting noise on an image from outside the dataset 
Steps: 
 
  1-	Add noise to the image, and pass it through the autoencoder

  2-	Pass the image as it is without noise through the encoder part, then add noise to the encoded vector, then decode it.

  3-	Apply point (1), (2) on 3 or more custom images (outside of the dataset) and show and compare the decoded images with the original.
