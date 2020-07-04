### Project Description:
In this project, I have demonstrated compressing an image using the K means algorithm. It is an unsupervised algorithm that is used to sperate unlabelled data. The interactive control allows us to select an image and then set the k value using a slider. This project was a part of the Machine learning course that I took on Coursera.

### Images

### 1. Input color space : Over 16 million possible Colors
![](images/IC_1.png)<br/>

In the above image we observe that there are many colors present and there is smooth transition over image from one color to another. Using k means we will see that there is lack of diversity in the colors so using k means we will reduce the colors so as to compress the image and then visualize the color space.


### 2. Reduced color space.
Now we can see clear transitions from one color to other and also not so rich in colors as there are only 16 colors.
Below is the sample compressed image compared with an original image where K value is set by default as 16:


![](images/IC_2.png)<br/>

### 3. Below is the  compressed image compared with an original image where K value is set by default as 16. The k value can be changed using an interactive slider to set the k value.

![](images/IC_3.png)<br/>


### Key Points
   • We have pixels as a group in an image by their similar id in color to reduce the total no of colors in that image. So each cluster centroid is representative of 
     a color vector in RGB color space of its respective color.
     
   • The default k value set in the program is 16 clusters or 16 colors. k means unsupervised algorithm is used to sperate unlabelled data like image colors into   
     distinct groups.
     
   • Compression performed will be lossy, so fine details in an image are lost. A higher value of k can be set to minimize the loss.

### Alternative Approaches
   • Reducing frequency of image
   
   • Reducing intensity ranges of pixels



For more details see [Image-Compression-using-K-Means](https://github.com/smit-collab/Image-Compression-using-K-Means).




