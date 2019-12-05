# House price prediction
## Using Steepest in Matlab to optimize the objective function 
    The function can predict the house price when you input the amount of bedroom and bathroom.
    In the command line, we should input the content:
    syms x1 x2 x3;
    X = [x1;x2;x3];
    fx = (x1+2*x2+x3-18900)^2+(x1+3*x2+x3-22190)^2+(x1+4*x2+3*x3-32250)^2+(x1+3*x2+x3-23000)^2+(x1+3*x2+3*x3-28000)^2;
    x1 = [6000;3000;3000];
    e = 0.01
    min = House_price_prediction(fx,X,x1,e)
    
    
    
## Using RandomForest and Xgboost to do the prediction of house price in Python
### overview:
    1.Dataset read and clean
    2.Data Visualization and preprocessing
    3.Feature Engineering
    4.Optimize the parameter in RandomForest and Xgboost by randomsearch in sklearn and then Stacking
    5.Compare the difference and output the prediction of the house price
The input folder contains the dataset we used and our output of prediction.
