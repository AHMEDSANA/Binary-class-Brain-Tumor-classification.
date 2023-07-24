# Classification of Brain Tumor

### Binary Classification: 


As classification is an important part as we want to distinguish if an image has a tumor not. So, we can say if the brain is healthy or not. We used CNN for classification as given below:

We used Kaggle dataset. We used 10 epochs for training our dataset and with 11000 Training iimges and 200 Testing images. The accuracy achieved for both Testing and Training. 

The number layers which we used were self-designed but you can also use other models such as AlexNet, VGG, Inception, ResNet etc the model summary is given below:

<p align="center">
<img width="" height="" src="https://user-images.githubusercontent.com/73955220/211172692-2f71e7cb-c662-4714-bdfa-4894f91dd5d0.png">
</p>

### Implementation:

To implement this code you need basic or no knowledge of Convolution NUeral Network.
And all the libraries used in this code are basic Nueral Network Libraries. You can either train it on your own PC or use google colab for the training process and use there GPUs for training.
You just have to download the code file give it locaion of your dataset and run the code if all the libraries are installed on your PC or just run it on colab if you dont want to install the libraries on your PC. You can also change this code to classify for more than two classes with ease. 

**Libraires used:**

 1-Numpy
 
 2-Pandas
 
 3-Keras
 
 4-OpenCv
 
 5-Tensorflow
 
 6-Matplot

### Results

**TABLE1: CLASSIFICATION OF BRAIN TUMOR**

<p align="center">
<img width="" height="" src="https://user-images.githubusercontent.com/73955220/211172060-42d3efb8-5200-402a-a85e-21c6fccc54b4.png">
</p>

### Graph and results for classification:

**Testing and Training Accuracy:**

<p align="center">
<img width="" height="" src="https://user-images.githubusercontent.com/73955220/211172150-e03c310c-9a07-4ae9-b7db-bcb5fb4f55e2.png">
</p>

**Training and Testing Loss:**

<p align="center">
<img width="" height="" src="https://user-images.githubusercontent.com/73955220/211172204-10c5ae94-117d-45ec-ad20-b72f915a5d10.png">
</p>

**Few Testing Images:**

<p align="center">
<img width="" height="" src="https://user-images.githubusercontent.com/73955220/211172260-19b9eb6a-034f-439d-9e72-8559de30f910.png">
</p>

We cross-validated our CNN classification model on another Kaggle dataset of 160 Test tinges for achieving the result. As we can see from the table that the CNN model we used and the number of layers are giving us the best result in after cross validation proving the great efficiency and predictability of our model.
 

**Cross-validation-Classification outputs:**

<p align="center">
<img width="" height="" src="https://user-images.githubusercontent.com/73955220/211172487-56d5f067-535e-40aa-8006-cc415fb6e4ea.png">
</p>

<p align="center">
<img width="" height="" src="https://user-images.githubusercontent.com/73955220/211172518-5c514554-1870-4ec8-8c52-2b3357573ad8.png">
</p>

## Running of Code
You can run the code by just downloading the notebook and running it on Jupyter or upload on Google Colab and run it over there but you will have to change the dataset location link in the code and also change the model save and load location according to your own device from the code. I have already linked the dataset above.
