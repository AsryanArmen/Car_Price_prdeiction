# Car_Price_prdeiction
Machine Learning


----------
|Overview|
------------
The purpose of this competition is to guess the price of a car using its characteristics.
Not all characteristics can be used when predicting the price. Make predictions using machine learning algorithms or deep learning networks.

----------
|Evaluation Metric|
------------
The evaluation criterion for this competition is the Mean Absolute Error, which calculates the modulus of the difference between the predicted value and the actual value for all data and returns the mean of the sum.
MSE will be calculated between the submit prediction and the actual price. Submit prediction should have 2 columns:

    1.the vehicle Id in test.csv
    2.the predicted price.

----------
|Dataset Description|
------------
The data was collected from the auto.am website. Each car has 8 characteristic columns:
Year, Motor type, Mileage, Wheel, Color, Car_type, Status, Motor volume
There are 5 types of cars:

------------------------
| Run Code              |
------------------------
1. py -m venv venv (if you have windows pc)
   
   a) .\venv\Scripts\activate
   
   b) py -m pip install --upgrade pip
   
   c) pip install jupyter numpy pandas seaborn matplotlib scikit-learn tensorflow
   
   d) jupyter-notebook (For open jupyter)
2. python3 -m venv venv (if you have mac or linux)

   a) source ./venv/bin/activate
   
   b) python3 -m pip install --upgrade pip
   
   c) pip install jupyter numpy pandas seaborn matplotlib scikit-learn tensorflow
   
   d) jupyter-notebook (For open jupyter)

    1.Toyota Camry
    2.Mercedes-Benz C class
    3.Hyundai Elantra
    4.Nissan Rogue
    5.Kia Forte
