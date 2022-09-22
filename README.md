# Neural_Network_Charity_Analysis

Purpose

Overall, our goal here was to devise a neural network to aid in the determination of organizations that would be best suited for recieving funds from the Alphabet Soup Charity. This netowrk was trained utilizing data that had been generated previously from organizations that had been awarded and denied funding.

Results

1.  What variable(s) are considered the target(s) for your model?

The IS_SUCCESSFUL column is the target of model.

2.  What variable(s) are considered to be the features for your model?

All columns are considered features other than IS_SUCCESSFUL.

3.  What variable(s) are neither targets nor features, and should be removed from the input data?

The two which were removed initially was EIN & NAME that were neither targets nor features.

4.  How many neurons, layers, and activation functions did you select for your neural network model, and why?

Two layers were selected and the activation chosen was Relu considering it was the best at producing accurate result.

5.  Were you able to achieve the target model performance?

Overall the model achieved 69%. 

6.  What steps did you take to try and increase model performance?

First, to increase the units and add more layers to see if model will accuracy but it did not. Second, try changing the activation type but did not affect the performance. Instead it decreased it. Third, try adding more layers and increase the units. 

Summary

It appears the model was over fitted judging from the 66% (post optimization) and 69% (initial) accuracy levels. One other model which could be utilized would be the Random Forest Clusters model and performing various trial and error scenarios to see if the over fittnes could be brought down.
