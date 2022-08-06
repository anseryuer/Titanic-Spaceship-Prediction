# Titanic-Spaceshit-Prediction
Competition Available on Kaggle.

The competition is on Kaggle. https://www.kaggle.com/c/spaceship-titanic

The 3 CSV files, including sample_submission.csv, train.csv and test.csv are given in the website above.

Preprocessing_Visualizing.ipynb preprocessed data in the train.csv and test.csv because the data needs to be standardized and normalized. There are also many missing values.
In the Preprocessing_Visualizing.ipynb, missing values are filled in and all the numbers are processed to make sure that they have a average value of 0 and STD value equal to one.
png 
I split the data in train.csv to after2.csv and after.csv and therefore, I can see accuracy of prediction on the validation dataset(testafter.) of the neural network, NN.
fit.ipynb and fitting.ipynb are two files that have the same functions.
The result is stored in the final.csv.

Data is visualized using Seaborn. The result is in pairplot1.png and pairplot2.png

Training process

![37c0ff00-edaa-4c50-a81f-9767ca75f005](https://user-images.githubusercontent.com/81740803/183241614-51a6c1bc-b853-4f8b-8448-a9e346990fdf.png)

Submission Result

![image](https://user-images.githubusercontent.com/81740803/183241636-208c8378-a0a0-4c9a-8d07-cf77096231e5.png)
