# Neural_Network_Charity_Analysis

### Background
We were attempting to create a deep learning model that could predict the success of applications to Alphabet Soup's fundraising. We used data from previous applications to determine whether our model is accurate enough for this purpose. In order to accomplish this, we used Tensorflow in Jupyter Notebook.

### Results
![RESULTS](https://github.com/shaneabbley/Neural_Network_Charity_Analysis/blob/main/results.png)
#### Data Preprocessing
* The IS_SUCCESSFUL column was out target variable.
* The STATUS, ASK_AMT, APLLICATION_TYPE, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, AFFILIATION, and SPECIAL_CONSIDERATIONS columns were our model feature's.
* The identificatoin columns EIN and NAME were removed as they would not contribute to our models success.
#### Compiling, Training, and Evaluating the Model
* I ended up using one hidden layer containing 20 neurons and a relu activation function. The relu performed the best and 20 neurons seemed to be a sweet spot. Also, increasing the number of layers decreased the accuracy of my model.
* I was only able to acheive a accuracy of 71.17%.
* I altered nearly all combinations of the variables mentioned and was not able to achieve a higher accuracy score. Specifically, I tried all standard activation functions in variuos numbers of hidden layers with various numbers of neurons. Perhaps there is something I missed or a combination I did not attempt.

### Analysis
Unfortunately, we were unable to achieve the desired accuracy goal. Perhaps a simpler binomial classification supervised machine learning model would better predict the outcome of these loans. The data is not too extensive for this recomondation and it would be a fairly quick test.
