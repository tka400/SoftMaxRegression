## SoftMaxRegression

Algorithm for multiclass classification problem, based on Linear Regression with gradient descent.

You can follow me on YouTube (на Русском) and write this ML algorithm from scratch in Python.

[![Alt text](https://img.youtube.com/vi/8LEM5CAL8Ns/mq3.jpg)](https://www.youtube.com/watch?v=8LEM5CAL8Ns)

For multiclass problem it one hot encodes target. The result of that models passed through SoftMax function.
The highest value is being selected as a predicted class .

This implementation plots test train errors

![picture 1](error.png)

Also plots classification results

![picture 2](classification.png)
