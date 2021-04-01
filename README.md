# Image Enhancement Using Fuzzy Logic

We can enhance the colors in an image by tunning two things brightness and contrast, this algorithm devided the image into fuzzy 
windows and every pixel has a membership degree to every window, the membership degrees are calculated depending on 
the distance between the window and the pixel, then the means and variances are calculated with respect to the membership degrees,
the final image is obtained by summing up the images of every fuzzy window in a weight way, the weights used are membership degrees.

## Results
- Grayscale Image Enhancement :

![alt text](https://github.com/pankaj846/Fuzzy_Logic_Image_Enhancement/blob/main/images/result_einstein.PNG)

- RGB Image Enhancement:

![alt text](https://github.com/pankaj846/Fuzzy_Logic_Image_Enhancement/blob/main/images/result_phone.PNG)
