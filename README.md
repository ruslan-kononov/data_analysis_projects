# Guided Project: Predicting Car Prices with the KNN Algorithm
## Motivation
In this guided project, I will explore the fundamentals of Machine Learning (ML) using the k-nearest neighbors (KNN) algorithm to predict a car's market price using a set of attributes. This project also aims to demonstrate my Python skills acquired due to ML Fundamentals online course that are a part of the Dataquest's <a href='https://www.dataquest.io/path/data-scientist/'>Data Science in Python</a> track.
## Description
In this project, I will be working with the data set that contains information on various cars. For each car we have information about the technical aspects of the vehicle such as the motor's displacement, the weight of the car, the miles per gallon, how fast the car accelerates, and more. 
You can read more about the data set  <a href='https://archive.ics.uci.edu/ml/datasets/automobile'>here</a> and can download it directly from <a href='https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data'>here</a>.

__Attribute Information__:

1. `symboling`: -3, -2, -1, 0, 1, 2, 3.
2. `normalized-losses`: continuous from 65 to 256.
3. `make`: alfa-romero, audi, bmw, chevrolet, dodge, honda, isuzu, jaguar, mazda, mercedes-benz, mercury, 
mitsubishi, nissan, peugot, plymouth, porsche, renault, saab, subaru, toyota, volkswagen, volvo
4. `fuel-type`: diesel, gas.
5. `aspiration`: std, turbo.
6. `num-of-doors`: four, two.
7. `body-style`: hardtop, wagon, sedan, hatchback, convertible.
8. `drive-wheels`: 4wd, fwd, rwd.
9. `engine-location`: front, rear.
10. `wheel-base`: continuous from 86.6 120.9.
11. `length`: continuous from 141.1 to 208.1.
12. `width`: continuous from 60.3 to 72.3.
13. `height`: continuous from 47.8 to 59.8.
14. `curb-weight`: continuous from 1488 to 4066.
15. `engine-type`: dohc, dohcv, l, ohc, ohcf, ohcv, rotor.
16. `num-of-cylinders`: eight, five, four, six, three, twelve, two.
17. `engine-size`: continuous from 61 to 326.
18. `fuel-system`: 1bbl, 2bbl, 4bbl, idi, mfi, mpfi, spdi, spfi.
19. `bore`: continuous from 2.54 to 3.94.
20. `stroke`: continuous from 2.07 to 4.17.
21. `compression-ratio`: continuous from 7 to 23.
22. `horsepower`: continuous from 48 to 288.
23. `peak-rpm`: continuous from 4150 to 6600.
24. `city-mpg`: continuous from 13 to 49.
25. `highway-mpg`: continuous from 16 to 54.
26. `price`: continuous from 5118 to 45400.

## Outcomes
In this project:
- I __analysed and cleaned a dataset__ containing information on 205 cars;
- I __trained and tested a univariate KNN model__ with various input features __to predict the target column__ `price`.
- Based on the RMSE values from the univariate KNN model, I __selected the most informative input features and fed them into a multivariate KNN model__;
- I __trained and tested a multivariate KNN model with various values of the hyperparameter__ `k` __and different validation approaches__ (holdout and k-fold validation).

<a href="https://nbviewer.jupyter.org/github/ruslan-kononov/Guided-Project-Predicting-Car-Prices/blob/fef9ad457d804a64d41f73946d22b301226cf8ae/Predicting%20Car%20Prices.ipynb">Click here to view the jupyter notebook file</a>
