# Neural Network Charity Analysis

## Overview of the analysis: 
During this project, we will be helping Beks create a data driven solution from a neural network to help stop companies from taking the foudations money and not using is affectively. 

## Results: 

### Data Preprocessing
---------
What variable(s) are considered the target(s) for your model?

  •	EIN and NAME—Identification columns

  •	APPLICATION_TYPE—Alphabet Soup application type

  •	AFFILIATION—Affiliated sector of industry

  •	CLASSIFICATION—Government organization classification

  •	USE_CASE—Use case for funding

  •	ORGANIZATION—Organization type

  •	STATUS—Active status

  •	INCOME_AMT—Income classification

  •	SPECIAL_CONSIDERATIONS—Special consideration for application

  •	ASK_AMT—Funding amount requested

  •	IS_SUCCESSFUL—Was the money used effectively

What variable(s) are considered to be the features for your model?

  •	ASK_AMT, CLASSIFICATION , and APPLICATION_TYPE
  
  ![app and class](https://user-images.githubusercontent.com/88864493/152919063-c196fbd7-a3c0-4070-95a0-fc8d34364c76.png)

What variable(s) are neither targets nor features, and should be removed from the input data?

  •	“EIN" and  "NAME"
  
  ![dropping](https://user-images.githubusercontent.com/88864493/152919099-6ff148f2-ca44-4b95-bf74-bfff13bf720c.png)

### Compiling, Training, and Evaluating the Model
_________
How many neurons, layers, and activation functions did you select for your neural network model, and why?

  •	![number](https://user-images.githubusercontent.com/88864493/152918988-4dd10fe7-66a4-4bef-9ef6-6eaafc32d4c4.png)


Were you able to achieve the target model performance?

  •	No I was at stuck at 68% after changing the numbers it dropped to 55%

What steps did you take to try and increase model performance?

  •	I attempted to change the hidden layers but that did not put me above 68%

## Summary: 

To summarize, I believe a different model should be used as the as the accuracy rate was not meeting the minimum percentage. I used the same numbers the first time running it and it came in at 52% and then I dropped the number significantly and it went up to 55%. Then returned to the original numbers once again to get 68%. The randomness is not something needed when it comes to accuracy as accuracy needs to be spot on every time. 
