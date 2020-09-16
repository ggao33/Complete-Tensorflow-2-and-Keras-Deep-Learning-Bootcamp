# Complete-Tensorflow-2-and-Keras-Deep-Learning-Bootcamp
This course will guide you through how to use Google's latest TensorFlow 2 framework to create artificial neural networks for deep learning! This course aims to give you an easy to understand guide to the complexities of Google's TensorFlow 2 framework in a way that is easy to understand.

## Section 0-2: Numpy, Pandas and Data Visualization
These three sections review numpy, pandas, seaborn and matplotlib for data preprocessing and data visualization. 

## Section 3: Artifical Nerual Network
Based on LendingClub DataSet from Kaggle: [https://www.kaggle.com/wordsforthewise/lending-club](https://www.kaggle.com/wordsforthewise/lending-club) an ANN model is built to predict whether a borrower will be able to pay back their loan. There are many data preprocessing operation has been done to remove unnecessary features such as emp_length shown below:
![GitHub Logo](/result_pics/3-1.png)
![GitHub Logo](/result_pics/3-2.png)
Loss, validation loss vs training time diagram is attached for model evaluation.
![GitHub Logo](/result_pics/3-3.png)

## Section 4: Convolutional Neural Network
In this section, MNIST(Grascake images), CIFAR10(Color Images) datasets are used for training CNN which helps reduce parameters by focusing on local connectivity. ALso pooling layer is added after convolutional layer in the model to help reducing large amount of parameters.
[Cell images taken from official NIH wensite](https://drive.google.com/open?id=1rXrgUzzIdsyJ4xp05Suq7ioR5q1tOtFY) are examples to deal with real image files which feed into the model in batches due to large groups of images. It resizes raw images and train the model to predict which cell is infected or not. 

![GitHub Logo](/result_pics/4-1.png)

The assessment task is to build an image classifier with Keras and Convolutional Neural Networks for the Fashion MNIST dataset. This data set includes 10 labels of different clothing types with 28 by 28 grayscale images. There is a training set of 60,000 images and 10,000 test images.

![GitHub Logo](/result_pics/4-2.png)

## Section 5: Recurrent Neural Networks
RNN are effective for processing sequence data(e.g. time-stamped sales data, sequence of text, heat beat data, etc...). And LSTM(Long Short Term Memory) neuron units can help fixing gradient issues. Both of RNN and LSTM are used to forecast Sine wave.
![GitHub Logo](/result_pics/5-1.png)
![GitHub Logo](/result_pics/5-2.png)

Time series example is taken from real world and relevent information is provided:
Release: Advance Monthly Sales for Retail and Food Services
Units: Millions of Dollars, Not Seasonally Adjusted

Frequency: Monthly

The value for the most recent month is an advance estimate that is based on data from a subsample of firms from the larger Monthly Retail Trade Survey. The advance estimate will be superseded in following months by revised estimates derived from the larger Monthly Retail Trade Survey. The associated series from the Monthly Retail Trade Survey is available at [https://fred.stlouisfed.org/series/MRTSSM448USN](https://fred.stlouisfed.org/series/MRTSSM448USN)

Information about the Advance Monthly Retail Sales Survey can be found on the Census website at [https://www.census.gov/retail/marts/about_the_surveys.html](https://www.census.gov/retail/marts/about_the_surveys.html)

Suggested Citation: U.S. Census Bureau, Advance Retail Sales: Clothing and Clothing Accessory Stores [RSCCASN], retrieved from FRED, Federal Reserve Bank of St. Louis; [https://fred.stlouisfed.org/series/RSCCASN](https://fred.stlouisfed.org/series/RSCCASN), November 16, 2019.

The historical Montly Sales data looks like:
![GitHub Logo](/result_pics/5-3.png)

Taking advantage of RNN, we forcast the Sales trend based on historical data:
![GitHub Logo](/result_pics/5-4.png)

## Section 6: NLP and Text Data
The Structure of text in William Shakespeare's work is learned in GRU in order to forget gate with fewer parameters compared to LSTM. Text can also be generated based on our model with given keywords.
![GitHub Logo](/result_pics/6-1.png)

## Section 7: Autoencoders
Autoencoders are applied on image noise removal and learning food habit in the UK.
![GitHub Logo](/result_pics/7-1.png)
![GitHub Logo](/result_pics/7-2.png)
![GitHub Logo](/result_pics/7-3.png)
![GitHub Logo](/result_pics/7-4.png)

## Section 8: Generative Adversarial Networks
MNIST images are trained through GANs and DCGANs. There are some generated images:
![GitHub Logo](/result_pics/8-1.png)
![GitHub Logo](/result_pics/8-2.png)
![GitHub Logo](/result_pics/8-3.png)

## Section 9: Deployment
-Create a Model
-Exporting a Model
-Creating a Callable API
-Calling the API with Postman
-Calling the API with Python
-Calling a model through Flask
-Launching a full ML App to the web

