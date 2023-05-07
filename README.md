# deep-learning-challenge
Purpose: to help the nonprofit foundation Alphabet Soup to determine the chance of funding successsful for its applicants by building a neural network model with higher than 75% accuracy. 

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
What variable(s) are the features for your model?
What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Model 1 
- First layer with 80 neurons and relu activation function
- Second layer with 30 neurons and relu activation function
- Train model with 100 epoches
- 72.7% accuracy comparing the model prediction with the true values.  
- <img width="624" alt="image" src="https://user-images.githubusercontent.com/118244319/236704483-822023a8-6c2e-4a1a-a211-9ed43e8aaca2.png">


Model 2 - try with different activation function and higher epoches
- First layer with 80 neurons and tanh activation function
- Second layer with 30 neurons and tanh activation function
- Train model with 200 epoches
- 72.5% accuracy comparing the model prediction with the true values.  
- <img width="613" alt="image" src="https://user-images.githubusercontent.com/118244319/236704612-8b52d761-8bca-4eb9-a68c-b8e8465fdf74.png">


Model 3 - try with more layers, higher epoches, more neurons
- First layer with 110 neurons and relu activation function
- Second layer with 100 neurons and relu activation function
- Third layer with 100 neurons and relu activation function
- Fourth layer with 100 neurons and relu activation function
- Fifth layer with 100 neurons and relu activation function
- Train model with 200 epoches
- 72.6% accuracy comparing the model prediction with the true values. 
- <img width="606" alt="image" src="https://user-images.githubusercontent.com/118244319/236704873-c334e36e-4801-45c3-96b6-57f626a96b24.png">

