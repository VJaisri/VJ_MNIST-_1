
End-to-End Machine Learning model for MNIST.

When it comes to classifying the digits that are handwritten MNIST plays it's role to predict the respective number and gives the exact answer.


MNIST Digits - Classification Using SVM(Support Vector Machine)

Objective: 
      To develop a model using Support Vector Machine which should correctly classify the handwritten digits from 0-9 based on the pixel values given as features. Thus, this is a 10-class classification problem.
      
Data Description: 
      For this problem, using MNIST data which is a large database of handwritten digits. The 'pixel values' of each digit (image) comprise the features, and the actual number between 0-9 is the label.
      
Since each image is of 28 x 28 pixels, and each pixel forms a feature, there are 784 features. MNIST digit recognition is a well-studied problem in the ML community, and people have trained numerous models (Neural Networks, SVMs, boosted trees etc.) achieving error rates as low as 0.23% (i.e. accuracy = 99.77%, with a convolutional neural network).

Before the popularity of neural networks, though, models such as SVMs and boosted trees were the state-of-the-art in such problems.

First explore the dataset a bit, prepare it (scale etc.) and then experiment with linear and non-linear SVMs with various hyperparameters.

Dividing the analysis into the following parts:

Data understanding and cleaning: Data preparation for model building Building an SVM model - hyperparameter tuning, model evaluation etc.

SVM (Support Vector Machine):
  Support Vector Machine (SVM) is a supervised machine learning algorithm capable of performing classification, regression and even outlier detection. The linear SVM classifier works by drawing a straight line between two classes.
  
  The End-to-End model deployed through Flask and the front-end is completely developed through HTML and CSS.
  
Conclusion:  
  The accuracy achieved using a non-linear kernel (~0.94) is mush higher than that of a linear one (~0.91). We can conclude that the problem is highly non-linear in nature.
