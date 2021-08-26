Audible App for Book Genre Recommendations.

Initial Source: Rohit Dass (6/14/2021). "Audible Dataser", https://www.kaggle.com/rohitdass/audible-dataset.

Description: Initial full dataset for audible dataset recommendation engine. Total books 2200+(Including Duplicates). Then, using pandas 100 random human demographics were generated and merged to the initial source. The generated demographics were then merged to the initial source to create the "dataset_Exploded" dataset. After this final dataset was cleaned.

Variables/Columns GENDER: Gender Male or Female AGE: Age Range 18-75 ZIP CODE: random 5 digit in 80201,80239 range INCOME: <200000K

Next we cleaned and encoded the data, using pandas get dummies.

After that, we used Tableau to make visual descriptions of the demographics by gender, age, book popularity, and financials.

Finally, we used machine learning to make predictions on the top five book genres. We shaped the data using gender, age, zip code of users and book ratings with number of book ratings. We used 40% of the total data to test on to avoid overfitting the models. The accuracies of the top five book categories were all between 80 to 90%, so we are able to say that if we know the user's age, zip code, gender, and book ratings and number of ratings we can predict with 80-90% accuracy if the top five book category will be chosen.

After that, we used Random Forest to find the selective features to be Zip Code (or location) as the most important for High Review of the books and for the choice of the top book category of Literature and Fiction. 

