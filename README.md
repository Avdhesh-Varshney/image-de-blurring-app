<h1 align='center'>💥 Image De-Blurring Application 💥</h1>

<div align='center'>

### :zap: **TECH STACK USED** 

![Python](https://img.shields.io/badge/python-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=for-the-badge&logo=Streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)

</div>

![Line](https://user-images.githubusercontent.com/85225156/171937799-8fc9e255-9889-4642-9c92-6df85fb86e82.gif)

## :zap: **ABOUT THE APPLICATION**

**_Face deblurring operation_** _is the task of estimating a clear image from its degraded blur image and recovering the sharp contents and textures._ The **aim of face deblurring** is to restore clear images with more explicit structure and facial details. The face deblurring problem has attracted considerable attention due to its wide range of applications.

| Blurred Image | Processing | Clear Image |
|---------------|------------|-------------|
| ![image](https://user-images.githubusercontent.com/78999467/115102986-2b809c80-9f6e-11eb-82f7-e6a5a5de3f85.png) | ![image](https://user-images.githubusercontent.com/78999467/115102966-04c26600-9f6e-11eb-841d-994a925343c6.png) | ![image](https://user-images.githubusercontent.com/78999467/115102989-33404100-9f6e-11eb-832e-91348d7a0b7c.png) |

## :zap: **MODELS USED**

| Models Used         | Accuracy |
|---------------------|----------|
| Autoencoder Model   | 89.80%   |
| De-Blur CNN Model   | 78.20%   |

## :zap: **WHAT I HAVE DONE**

1) Training an End-to-End model for deblurring of images (CelebA) following the work in CNN For Direct Text Deblurring, using Keras.
    - The first layer filter size is adjusted to be approximately equal to the blur kernel size. Pre-Trained model with weights and some images from test set are uploaded.

2) Importing Necessary Packages 
3) Loading Images Dataset in the model 
    - Only showing a small set of images from the local test set we generated.

4) Loading input blurred and clear images 
  ![image](https://user-images.githubusercontent.com/78999467/115102547-430a5600-9f6b-11eb-9691-74045164dbbc.png)

5) Defining CNN Model for Training Model 
    - The model has been trained on a much larger dataset of CelebA images.
    - Loaded the weight file `autoencoder_weights.keras`

6) Deblurred Faces 
    - Deblurred images as output 
  ![image](https://user-images.githubusercontent.com/78999467/115102584-8fee2c80-9f6b-11eb-8db9-068dc3ab2ff6.png)

![Line](https://user-images.githubusercontent.com/85225156/171937799-8fc9e255-9889-4642-9c92-6df85fb86e82.gif)

## :zap: **RESULTS** 

### :zap: De Blur CNN Model 

<table>
  <tr>
    <td><img src="./Images/De-Blur-Model-Accuracy.png" alt="Accuracy"></td>
    <td><img src="./Images/De-Blur-Model-Loss.png" alt="Loss"></td>
  </tr>
  <tr>
    <td colspan="2" style="text-align: center;"><img src="./Images/deblur_result.png" alt="Deblur Result"></td>
  </tr>
</table>

### :zap: Auto encoder CNN Model 

<table>
  <tr>
    <td><img src="./Images/Autoencoder-Model-Accuracy.png" alt="Accuracy"></td>
    <td><img src="./Images/Autoencoder-Model-Loss.png" alt="Loss"></td>
  </tr>
  <tr>
    <td colspan="2" style="text-align: center;"><img src="./Images/autoencoder_result.png" alt="Autoencoder Result"></td>
  </tr>
</table>

### :zap: Preview of Website 

![screenshot](./Images/Screenshot.jpeg)

### :zap: Predictions Done by Website 

<table>
  <tr>
    <td><img src="./Images/sample_0.jpg" alt="0" style="width:300px;"></td>
    <td><img src="./Images/output_image_0.png" alt="0" style="width:300px;"></td>
    <td><img src="./Images/clear_0.jpg" alt="0" style="width:300px;"></td>
  </tr>
  <tr>
    <td><img src="./Images/sample_169.jpg" alt="169" style="width:300px;"></td>
    <td><img src="./Images/output_image_169.png" alt="169" style="width:300px;"></td>
    <td><img src="./Images/clear_169.jpg" alt="169" style="width:300px;"></td>
  </tr>
  <tr>
    <td><img src="./Images/sample_1004.jpg" alt="1004" style="width:300px;"></td>
    <td><img src="./Images/output_image_1004.png" alt="1004" style="width:300px;"></td>
    <td><img src="./Images/clear_1004.jpg" alt="1004" style="width:300px;"></td>
  </tr>
</table>

![Line](https://user-images.githubusercontent.com/85225156/171937799-8fc9e255-9889-4642-9c92-6df85fb86e82.gif)

<div align="center">
  <h3>Show some &nbsp;❤️&nbsp; by &nbsp;🌟&nbsp; this repository!</h3>
</div>

<a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-red?style=for-the-badge" align="right"/></a>
