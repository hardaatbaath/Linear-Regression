# Linear-Regression
This is a basic program that applies the mathematical concept of Linear Regression to a data set that has been provided along in the repository. The data set belongs to a Combined Cycle Power Plant and takes the following inputs:
 1. Ambient Temprature (AT)
 2. Vacuum (V)
 3. Ambient Pressure (AP)
 4. Relative Humidity (RH)</br>

And gives output of Electrical Energy Produced (EP) per hour.</br>
The program tries to come up with the best line of the form y = W.x + B, via the concept of Gradient Descent. The user has to input the learning rate and number of Epochs.</br>
The program then uses the prebuilt Linear Regression library of Sklearn, and applies the same data set to it as well.</br>
The accuracy of the model is predicted using the R squared value of the model.</br>
