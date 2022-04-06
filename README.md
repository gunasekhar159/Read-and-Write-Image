# READ AND WRITE AN IMAGE
## AIM
To write a python program using OpenCV to do the following image manipulations.
i) Read, display, and write an image.
ii) Access the rows and columns in an image.
iii) Cut and paste a small portion of the image.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Choose an image and save it as a filename.jpg
### Step2:
Use imread(filename, flags) to read the file.
### Step3:
Use imshow(window_name, image) to display the image.
### Step4:
Use imwrite(filename, image) to write the image.
### Step5:
End the program and close the output image windows.
## Program:
### Developed By:
### Register Number: 
i) #To Read,display the image
```
  import cv2
color_img=cv2.imread('n.png',1)
cv2.imshow('21221240014,M.Gunasekhar',color_img)
cv2.waitKey(0)

```
ii) #To write the image
```
import cv2
color_img=cv2.imread('n.png',1)
w=cv2.imwrite('1.png',color_img)
cv2.imshow('212221240014,M.Gunasekhar',color_img)
cv2.waitKey(0)


```
iii) #Find the shape of the Image
```python3
import cv2
colorImage = cv2.imread('n.png',1)
print(colorImage.shape)


```
iv) #To access rows and columns

```python3
[9:52 AM, 4/5/2022] typing......: colorImage = cv2.imread('n.png',1)
print(colorImage.shape)
[9:53 AM, 4/5/2022] typing......: import cv2
import random
color_img=cv2.imread('n.png',1)
for i in range(100):
    for j in range(color_img.shape[1]):
        color_img[i][j]=[random.randint(0,255),random.randint(0,255),random.randint(0,255)]
cv2.imshow('212221240014,M.Gunasekhar',color_img)
cv2.waitKey(0)


```
v) #To cut and paste portion of image
```python3
import cv2
import random
color_img=cv2.imread('n.png',1)
for i in range(100):
    for j in range(color_img.shape[1]):
        color_img[i][j]=[random.randint(0,255),random.randint(0,255),random.randint(0,255)]
cv2.imshow('212221240014,M.Gunasekhar',color_img)
cv2.waitKey(0)


```

## Output:

### i) Read and display the image

![output](https://github.com/gunasekhar159/Read-and-Write-Image/blob/main/n1%20g.JPG?raw=true)

### ii)Write the image

![output](https://github.com/gunasekhar159/Read-and-Write-Image/blob/main/n2%20g.JPG?raw=true)

### iii)Shape of the Image

![output](https://github.com/gunasekhar159/Read-and-Write-Image/blob/main/n3%20g.JPG?raw=true)

### iv)Access rows and columns
![output](https://github.com/gunasekhar159/Read-and-Write-Image/blob/main/n4%20g.JPG?raw=true)

### v)Cut and paste portion of image
![output](https://github.com/gunasekhar159/Read-and-Write-Image/blob/main/n5%20g.JPG?raw=true)

## Result:
Thus the images are read, displayed, and written successfully using the python program.


