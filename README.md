# deep-learning-challenge
Purpose: to help the nonprofit foundation Alphabet Soup to determine the chance of funding successsful for its applicants by building a neural network model with higher than 75% accuracy. 

Data Preprocessing
- drop the non-beneficial columns "EIN" and "NAME" 
- cutoff value based on 'APPLICATION_TYPE' count less than 500 as others 
- cutoff value based on 'CLASSIFICATION' count less than 1500 as others 
- pd.get_dummies to convert categorical data to numeric
- set "IS_SUCCESSFUL" as target and other as features 
- train_test_split to split the data into test and train dataset
- standardscaler to scale the dataset

Compiling, Training, and Evaluating the Model

Model 1 
- First layer with 80 neurons and relu activation function
- Second layer with 30 neurons and relu activation function
- Train model with 100 epoches
- 72.7% accuracy comparing the model prediction with the true values.  
<img width="624" alt="image" src="https://user-images.githubusercontent.com/118244319/236704483-822023a8-6c2e-4a1a-a211-9ed43e8aaca2.png">
- failed to achieve the target model accuracy 75%

Model 2 - try with different activation function and higher epoches
- First layer with 80 neurons and tanh activation function
- Second layer with 30 neurons and tanh activation function
- Train model with 200 epoches
- 72.5% accuracy comparing the model prediction with the true values.  
<img width="613" alt="image" src="https://user-images.githubusercontent.com/118244319/236704612-8b52d761-8bca-4eb9-a68c-b8e8465fdf74.png">
- failed to achieve the target model accuracy 75%

Model 3 - try with more layers, higher epoches, more neurons
- First layer with 110 neurons and relu activation function
- Second layer with 100 neurons and relu activation function
- Third layer with 100 neurons and relu activation function
- Fourth layer with 100 neurons and relu activation function
- Fifth layer with 100 neurons and relu activation function
- Train model with 200 epoches
- 72.6% accuracy comparing the model prediction with the true values. 
<img width="601" alt="image" src="https://user-images.githubusercontent.com/118244319/236705443-7772d3f6-8b3d-422e-8bc1-3f0589e0e65a.png">
- failed to achieve the target model accuracy 75%

