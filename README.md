# Linear Regression from Scratch
<hr>

Linear Regression is a supervised learning algorithm which is both a statistical and a machine learning algorithm. It is used to predict the real-valued output y based on the given input value x. It depicts the relationship between the dependent variable y and the independent variables xi  ( or features ).  The hypothetical function used for prediction is represented by h( x ).

<b>  h( x ) = w * x + b  </b>
    
          where, b is the bias.
                 x represents the feature vector
                 w represents the weight vector.
Linear regression with one variable is also called univariant linear regression.  After initializing the weight vector, we can find the weight vector to best fit the model by ordinary least squares method or gradient descent learning.

### Mathematical Intuition: 
<hr>

The cost function (or loss function) is used to measure the performance of a machine learning model or quantifies the error between the expected values and the values predicted by our hypothetical function. The cost function for Linear Regression is represented by J.

 ![quicklatex com-ee804dd2ef914445d34e803be76167a2_l3](https://github.com/Gokulprasanth-t/Linear-regression/assets/121724612/186a479f-8226-4faa-ae0b-31abf45ca544)

Here, m is the total number of training examples in the dataset.
y(i) represents the value of target variable for ith training example.

So, our objective is to minimize the cost function J (or improve the performance of our machine learning model). To do this, we have to find the weights at which J is minimum.  

