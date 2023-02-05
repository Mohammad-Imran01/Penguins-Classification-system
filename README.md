# Penguins web app deployed on Heroku

Check out the YouTube video showing the development of this web app at https://youtu.be/zK4Ch6e1zq8

The deployed web app is live at https://dp-penguins.herokuapp.com/

This web app predicts the species of penguins as a function of their input parameters (bill length, bill width, flipper length, body mass, sex and island).

The web app was built in Python using the following libraries:
* streamlit
* pandas
* numpy
* scikit-learn
* pickle


From the plot shown above, we can see that the random forest has incorrectly classified a total of 7 penguins out of the 114 in the test data. As shown in the classification report, we have therefore achieved an accuracy of 94%.



![Screenshot](https://github.com/Mohammad-Imran01/Penguins-Classification-system/blob/main/penguinsConfusion%20matrix.png)
