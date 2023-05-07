# Deep-Learning-Challenge
Purpose: to help the nonprofit foundation Alphabet Soup to determine the chance of funding successsfulness for its applicants by building a neural network model with higher than 75% accuracy. 

## Data Preprocessing
- drop the non-beneficial columns "EIN" and "NAME" 
- get the 'APPLICATION_TYPE' value count and then cutoff value if less than 500 as others 
- get the 'CLASSIFICATION' value count and then cutoff value if less than 1500 as others 
- pd.get_dummies to convert categorical data to numeric
- set "IS_SUCCESSFUL" as target and other as features 
- train_test_split to split the data into test and train dataset
- standardscaler to scale the dataset

## Compiling, Training, and Evaluating the Model

Model 1 
- First layer with 80 neurons and relu activation function
- Second layer with 30 neurons and relu activation function
- Train model with 100 epoches
- 72.5% accuracy comparing the model prediction with the true values
- failed to achieve the target model accuracy 75% 
<img width="590" alt="image" src="https://user-images.githubusercontent.com/118244319/236706133-38e91b71-9272-4b89-9a07-d2e598406452.png">



Model 2 - try with different activation function and higher epoches
- First layer with 80 neurons and tanh activation function
- Second layer with 30 neurons and tanh activation function
- Train model with 200 epoches
- 72.4% accuracy comparing the model prediction with the true values
- failed to achieve the target model accuracy 75% 
<img width="570" alt="image" src="https://user-images.githubusercontent.com/118244319/236706122-ffa4bf51-53d3-4abc-bbf7-d887242c4e5c.png">



Model 3 - try with more layers, higher epoches, more neurons
- First layer with 110 neurons and relu activation function
- Second layer with 100 neurons and relu activation function
- Third layer with 100 neurons and relu activation function
- Fourth layer with 100 neurons and relu activation function
- Fifth layer with 100 neurons and relu activation function
- Train model with 200 epoches
- 72.5% accuracy comparing the model prediction with the true values
- failed to achieve the target model accuracy 75% 
<img width="584" alt="image" src="https://user-images.githubusercontent.com/118244319/236706560-d30f4af1-52da-4d24-b281-6828b87101be.png">


## Summary 

All 3 models are failed to achieve the target model accuracy of 75% after trying to add more neurons, add more layers, add more epochs and change activation functions. Next step, we could try with different model. 

## Support and Thank You to

Instructors, TAs, Tutors, and Learning Assistants.
