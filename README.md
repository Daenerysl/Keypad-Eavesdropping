# <center>Keypad-Eavesdropping
## <center>Keypad eavesdropping based on mobile phone sensors
### Description of the experiment
  
Using the sensors data provided in '/SensorData' gained via side channel to train a model which can predict input from the user's keystroke sensor data.
### Procedure of the experiment

1. Load the data of each key and store them in a dictionary.
2. Find the separate of each key's data(each key's sensor data is divided by a null string).
3. Get the statistical characteristic as features and the corresponding label.
4. Distribute the train set and the test set.
5. Choose five different algorithm to train the model and evaluate their performances.
    + Multi-classification
    + SVM
    + Random Forest
    + Decision Tree
    + K-nn
6. Use t-sne algorithm to visualize the result on the test set.
### Addition

Despite the parameters we used in the code were the best result of our repeated experiments, if you find a parameter that can provide a better prediction, feel free to tell us.
Please forgive us for being beginners of AI, we'd appreciate if you would tell us your suggestions.
