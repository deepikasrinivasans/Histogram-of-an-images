# Histogram-of-an-images
## Aim
To obtain a histogram for finding the frequency of pixels in an Image with pixel values ranging from 0 to 255. Also write the code using OpenCV to perform histogram equalization.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:
Read the gray and color image using imread()

### Step2:
Print the image using imshow().



### Step3:
Use calcHist() function to mark the image in graph frequency for gray and color image.

### step4:
Use calcHist() function to mark the image in graph frequency for gray and color image.

### Step5:
The Histogram of gray scale image and color image is shown.


#### Program:
```
### Developed By: DEEPIKA S
### Register Number: 212222230028
```
<table>
  <tr>
    <td width=50%>
      
####  Histogram of Gray scale image and Color image  
```python
import cv2
import matplotlib.pyplot as plt
gray_image = cv2.imread("gray.jpg")
color_image = cv2.imread("color.jpg",-1)
cv2.imshow("Gray Image",gray_image)
cv2.imshow("Colour Image",color_image)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
</td>
<td>
  
#### Output:
![diptgray1](https://github.com/deepikasrinivasans/Histogram-of-an-images/assets/119393935/8d172f61-7d6a-4648-8d96-a5b8249b448b)
![color](https://github.com/deepikasrinivasans/Histogram-of-an-images/assets/119393935/ae8f505d-4f9f-4450-9364-e0916c4d9fba)
</td>
</tr>



<tr>
  <td width=50%>
  
### Input Grayscale Image and Color Image


### Histogram of Grayscale Image and any channel of Color Image



### Histogram Equalization of Grayscale Image.




## Result: 
Thus the histogram for finding the frequency of pixels in an image with pixel values ranging from 0 to 255 is obtained. Also,histogram equalization is done for the gray scale image using OpenCV.
