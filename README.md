
# Image Caption Generator: Project Overview
 ###### Whenever an image appears in front of us our brain is capable of annotating or labeling it, but what about computers? 
 ###### Now it is possible for computers to process an image and label it with a highly relevant and accurate caption.
 ###### •	Created a tool which is capable of generate very relevant captions for the image with the help of datasets.
 ###### •	Used two techniques of Deep learning including LSTM a type of Recurrent Neural Network and Convolutional Neural Networks (CNN).
 ###### •	This system includes the labeling of an image with English keywords with the help of datasets provided during model training. 
 ###### •	Flickr 8k dataset is used to train the CNN model called VGG16. 
 ###### •	VGG16 is responsible for image feature extraction. These extracted features will be fed to the LSTM model which in turn generates the image caption.
 
### Dataset:
 ###### •	Flickr 8k dataset is used to train the model
 ###### •	Which contain 8091 images with their id’s
 ###### •	This dataset also contains a caption file 
 ###### •	Caption file contain 5 captions for each image
 ###### Dataset link: https://www.kaggle.com/datasets/adityajn105/flickr8k
 
## Model Architectural Diagram:

![](https://user-images.githubusercontent.com/115410634/194777567-4ba3dc59-4632-4fe6-b450-4e4c12d15375.png)

### Dataset Preprocessing:
###### •	Convert images into a fixed size vector for passing into neural networks 
###### •	In the Captions data we have applied cleaning
###### •	Remove special characters
###### •	Add startseq and endseq
###### •	Create a vocabulary and count for words

Graph to visualize most frequent words
![image](https://user-images.githubusercontent.com/115410634/194777909-d5c19a91-4eb7-4475-ab7d-22614ba546a5.png)
 
 ### Model Diagram:
 ![model](https://user-images.githubusercontent.com/115410634/194778351-5df38f29-72fd-4f29-b24f-978ba382b703.png)







