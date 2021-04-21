# Image-Caption-Genrator
# Description 

Generating a caption for a given image is a challenging problem in the deep learning domain.
Image Caption Generator or Photo Descriptions is one of the Applications of Deep Learning. In Which we have to pass the image to the model
and the model does some processing and generating captions or descriptions as per its training. We need very high computational
power and a very huge dataset for better results. 

# Dataset

For training our model I’m using [Flickr8K](https://www.kaggle.com/adityajn105/flickr8k) dataset.
It consists of 8000 unique images and each image will be mapped to five different sentences which will describe the image.


# Approach 

1) Did preprocessing of the textual data .
2) Used CNN as the Encoder and LSTM as the decoder 
3) Made an ensemble model consisting of CNN as well as LSTM for my training purpose.


# Result 

##  Image 

![dog photo](https://user-images.githubusercontent.com/50076662/115613016-86691980-a309-11eb-8271-6db0781511eb.png)

## Output 
![output dog](https://user-images.githubusercontent.com/50076662/115613409-faa3bd00-a309-11eb-8aff-21859995e7ff.png)
