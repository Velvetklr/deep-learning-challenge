# deep-learning-challenge
![MIT](https://img.shields.io/badge/License%20-%20MIT%20-%20%234e8983)

## Overview
We are analyzing the given dataset in ordert to help select applicants to given funding to that have a better chance for success. 

## Table of Contents
- [Analysis](#questions)
- [Results](#results)
- [Summary](#summary)
- [License](#license)
- [Contact](#contact)


## Questions
### Data Preprocessing
* What variable(s) are the target(s) for your model? 
    IS_SUCCESSFUL is the target variable  

* What variable(s) are the features for your model? 
   NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL  

* What variable(s) should be removed from the input data because they are neither targets nor features?  
    The EIN variable should be removed.  

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?  
    There were 2 hidden layers, and the layers had 80 and 30 neurons in them. This gives it more computing power, but can get expensive. My chosen activations were 'relu' and 'sigmoid'.  
* Were you able to achieve the target model performance?  
    Yes, my accuracy was 75%

* What steps did you take in your attempts to increase model performance?  
    In the original model I dropped the 'NAME' feature. In order to increase the performance I added the 'NAME' feature back into the model and created bins. I also increased the neuron on the hidden layer 

## Summary
By adding the Name as a feature to the model. The applicant has a 75% chance of being successful. 

I tested with GradientBoosting and RandomForest,and I had better results with my current model. 

## License
MIT

## Contact
If there are any questions of concerns, I can be reached at:
##### [github: velvetklr](https://github.com/velvetklr)
##### [email: velvetklr@gmail.com](mailto:velvetklr@gmail.com)
