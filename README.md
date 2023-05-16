# Handwritten Devanagiri Digit Recognition

This team consists of <a href="https://github.com/DSS3113">Danish Singh Sethi</a>, <a href="https://github.com/mizoreto">Jiayin Meng</a>, and  <a href="https://github.com/ritikav2">Ritika Vithani</a>.<p>

This project uses machine learning to perform handwritten digit recognition for Devanagiri digits. We have executed this task using Python with three different algorithms: K-Nearest Neighbors (KNN), Support Vector Machines (SVM), and Convolutional Neural Networks (CNN). We have used the <a href="https://www.kaggle.com/datasets/anurags397/hindi-mnist-data">Hindi/Devanagari MNIST Data</a> available on Kaggle to train and test our dataset.<p>

The authors of the implementation of the algorithms are as follows:<br>
<ul>
  <li><b>Danish</b>: Convolutional Neural Networks</li>
  <li><b>Jiayin</b>: Support Vector Machines</li>
  <li><b>Ritika</b>: K-Nearest Neighbors</li>
</ul>

In addition, Danish has manually collected handwritten digits from 8 people as a supplement to the training dataset and from 10 people as a supplement to the testing dataset. It should be noted that all these people learnt how to write the Devanagiri script in school. These data points are available in the CustomTrain and CustomTest folders<p>

We observed that our CNN model performed best with an accuracy of 99.6% on training and testing using a concatentation of the Kaggle datasets and manually collected ones.
