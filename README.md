
## Introduction
#### Image processing

Image processing is the manipulation of digital images using algorithms to improve their quality or extract useful information. It is a broad field that encompasses a wide range of techniques and applications. Some common image processing tasks include:

- Enhancing image quality: This can include techniques such as denoising, deblurring, and color correction.

- Extracting features: This can include techniques such as edge detection, texture analysis, and object recognition.

- Compressing images: This involves reducing the size of an image file by removing redundant or unnecessary information.

- Segmentation: This involves dividing an image into multiple segments or regions of interest.

There are many tools and libraries available for image processing, including Python's Pillow library and OpenCV.
## Aim

The goal of this project is to practice basic image processing techniques using the OpenCV library. The focus will be on applying the following operations:

- Drawing shapes on an image
- Blending images
- Pasting images
- Template matching
- Edge detection
- Changing image thresholds
- Drawing contours
We will be using OpenCV to implement these techniques and explore their applications in image processing.
## Methods an Results
1. Drawing shapes on an image

    The first technique we will be practicing is drawing shapes on an image. To begin, we created a blank image with dimensions 512x512 and 3 color channels using the OpenCV library.

    We then used the library's drawing functions to draw a rectangle, circle, line, and text on the image. 

    The output of this operation is shown below."

    ![text on image](https://user-images.githubusercontent.com/118427592/210955161-8939ed63-5624-4582-b2ff-d5bd80a19085.png)

2. Blending images
   
    We blended two images of famous Malayalam actors, Mohanlal and Mamootty. The result of this operation is shown below.
    
    Input Images
    ![mamooty image](https://user-images.githubusercontent.com/118427592/210956064-dff7fced-de5c-4ef9-9e87-0db49786a1a4.png)

    Output Image
    ![blended image](https://user-images.githubusercontent.com/118427592/210956280-0a802884-7c48-4d79-9ab5-dabb2ad69317.png)
3. Pasting

    We paste OpenCV logo on blended image.
    
    OpenCV logo
    ![Logo](https://user-images.githubusercontent.com/118427592/210956516-9411955a-4e4e-4d5d-99ae-8199b78e5cf7.png)
Output
![pasting img](https://user-images.githubusercontent.com/118427592/210956603-2725baf9-c7da-4503-8f0d-9198dfb37e79.png)

4. Template Matching
    
    For template matching, we took an image of squirrel and take another image face of the squirel for template matching.
    
    methods we used are cv2.TM_CCOEFF, cv2.TM_CCOEFF_NORMED, cv2.TM_CCORR, cv2.TM_CCORR_NORMED, cv2.TM_SQDIFF, cv2.TM_SQDIFF_NORMED.
    
    The result of this operation is shown below.

    Input images
    ![templatematch 1](https://user-images.githubusercontent.com/118427592/210957624-4ed8408c-1d17-422a-970e-4b0fcc0c0985.png)

    Output 

    ![templatematch3](https://user-images.githubusercontent.com/118427592/210957725-f85235cf-b2f0-4c81-9f20-7ca3bcc9dc08.png)

![templatematch4](https://user-images.githubusercontent.com/118427592/210957773-5f6e8e05-9f62-4e83-b660-5172c0dd3c94.png)

![templatematch5](https://user-images.githubusercontent.com/118427592/210957809-4a5084bf-fe40-4e20-a196-54e3d4bb3b11.png)
![templatematch6](https://user-images.githubusercontent.com/118427592/210957853-21391c3b-e396-4b79-8d07-ba060c9fc227.png)
![templatematch7](https://user-images.githubusercontent.com/118427592/210957884-94d879b5-079a-4ee6-9ffa-c65d4d1b9bb4.png)

![templatematch8](https://user-images.githubusercontent.com/118427592/210957916-23f0658c-6bd4-4640-955f-4c22036a4685.png)

5. Edge Detection
We are using Canny edge detection to detect the edges of an input image in our project

Input Image
![edgedetection1](https://user-images.githubusercontent.com/118427592/210958319-a1a77507-2110-46f0-8879-3f8275a74270.png)

Output
![edgedetection2](https://user-images.githubusercontent.com/118427592/210958382-e234d644-9223-4fe5-802d-7ee2ddd04436.png)
