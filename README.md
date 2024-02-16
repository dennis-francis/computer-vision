<img src="https://github.com/dennis-francis/computer-vision/blob/main/207.jpg" height="300" width="800">

# computer-vision in convenience retail project

The objective of this project is to build a convenience store merchandising classifier. Given an image of c-store goods, think HBC, cigarettes, confectionary, chips, etc., ...can our model correctly classify it?  In summary, yes. I was able to use a vision transformer to achieve an accuracy of 95% on the hold-out test set.

## confectionary, chips, cigarettes image samples

Over 1300 images were scrapped from various sources on the web to build this project
<div style="display: flex;">
    <img src="https://github.com/dennis-francis/computer-vision/blob/main/candy%208.jpg" alt="confectionary" style="width: 23%;">
    <img src="https://github.com/dennis-francis/computer-vision/blob/main/chips.png" alt="chips" style="width: 23%;">
    <img src="https://github.com/dennis-francis/computer-vision/blob/main/cigs.png" alt="chips" style="width: 23%;">
</div>



## Model Architecture
A vision transformer is an AI model similar to ChatGPT, but reconfigured to work with images instead of text. Traditionally, convolutional neural networks (CNNs) have been used for computer vision tasks. However, when I ran tests on CNNs like ResNet and ConvNext (two popular CNN model architectures in the industry), the the performance results were very poor (see graph below)


<img src="https://github.com/dennis-francis/computer-vision/blob/main/model-results.png" alt="graph" height="400" width="600">


## Check out my work
To see the detail of my work and analysis, you can browse through these two files. The work was done using Jupyter Notebook and coded up in Python. 

[Exploratory Data Analysis and Wrangling of the c-store images](https://github.com/dennis-francis/computer-vision/blob/main/Capstone%203%20EDA%20and%20Wrangling%20Retail%20Photos.ipynb)

[Model Performance and results](https://github.com/dennis-francis/computer-vision/blob/main/Capstone%203%20Preprocessing%20%26%20Modeling.ipynb)
