# Neural Network Charity Analysis<br><br>
## Overview of the Analysis:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this analysis, we are showcasing deep-learning with the TensorFlow dependecy within Python. Overall we were able to analize and classify the success of charitable donations using the following:<br>
* Preprocessing the data for the nerual network model
* Train and evaluate the model
* Optimize the model
## Results<br>
_Data Preprocessing_
* The IS_SUCCESSFUL column shows the data to whether or not to if the charity donation was effective. These are then considered at the target of the deep learning nerual network.<br>
* Training and Testing have been applied to our model features, "APPLICATION_TYPE, AFFLIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL CONDIDERATION, ASK_AMT". 
* We removed the EIN and NAME columns to reduce unnecessary data.<br><br>
#
_Compiling, Training, and Evaluating the Model_<br>
* This deep-learning knowledge of neural community version is fabricated from hidden layers with 80 and 30 neurons respectively.
The enter facts has forty three capabilities and 25,724 samples.
The output layer is fabricated from a completely unique neuron as it's far a binary classification. To accelerate the education process, we're using the activation feature ReLU for the hidden layers. As our output is a binary classification, Sigmoid is used at the output layer.
* After running three different tests, we were not able to achieve the 75%. Which does not satisfy the performance to help predict the charity donation coucomes.
* To try and increase the model performance, I tried:
     - bucketing the feature ASK_AMT and organized the different intervals within the values
     - increased the number of neurons on one of the hidden layers, then used a model within the three hidden layers
     - tried the activation tanh fuction.<br>

Alas, none of these steps to improve the model's performance.<br>
<br>
## Summary<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With the results not outperforming the expected 75% accuratcy, the results overall were pretty average and the model is not outperforming its expectations. There could be opportunities to use supervised learning trees to find out if it would outperform our current deep learning model.
  
