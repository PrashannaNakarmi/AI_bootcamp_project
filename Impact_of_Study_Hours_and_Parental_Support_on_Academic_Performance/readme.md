# Impact of Study Hours and Parental Support on Grades 

## Information
- The info is stored in `info.txt`.
- The main process is in `main_file.py` while `proj.py` contains necessary methods. 

## Dataset
- I could not find necessary dataset, so had to create a pseudo dataset stored in `initial_data.csv`.

## Working
- After creating pseudo dataset and storing it, data cleaning is done to remove NaN or duplicated rows
- After that, a scatter plot of Study hours vs Final Grade is shown
- Then, a correlation graph is shown between all the parameters
- The training begins where I separated 20% data for testing and the rest for training
- Here, I used `Linear Regression` to perform regression and predict the testing data
- After which I evaluated `mse` and `r2` scores
- The coefficient and intercept were also evaluated to further predict grades based on user input

### User Input 
---
- The user is asked to input their study hours and parental support where study hours ranges from 0-40(inclusive) and parental support(Low, Medium, High) through `Predict Grade` button
- After user clicks predict, the predicted grade is shown
- The predicted grade can be saved if user clicks `Save prediction` button
- After saving the prediction, it is saved in `saved_predictions.csv` then two more buttons is seen `Show predictions` and `Show visualization` 
