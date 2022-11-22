# Implementing-Machine-Learning-Algorihtms

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Linear Regressions 
  
   Y = wX + b
        Y -> dependent variable 
        X -> independent variable
        w -> weight
        b -> bias

    Gradient Descent
        Optimization algorithm used for minimizing the loss function in various machine learning algorithms.
            w = w - Ldw
            b = b - Ldb
    
    Learning Rate
        Tuning Parameter in an optimization algorithm that determines the step size of each iteration while moving towards the minimum of a loss function
   
WORKFLOW OF THE REGRESSION MODEL :

    1. Set the learning rate and number of epochs, initiate weight and bias value.
    2. Build Linear Regression Equation (y = mx + b)
    3. Find the "y pred" value for rhe corresponding weight and bias
    4. Check the loss function for the parameter values
    5. Update the parameter values using Gradient Descent
    6. Repeat 3, 4, 5 till minimum loss function is reached
    
    
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
    
 # LOGISTIC REGRESSION

    Y_hat = 1/ 1+ e^-Z    where Z = w.X + b 

        Y_hat -> predicted value
        X -> independent variable
        w -> Weight
        b -> bias
    
    Gradient Descent:

        An optimizing algorithm used for minimizing the loss function in variou machine learning algorithms. Used for updating the parameters of the learning model.

        w = w - L*dw
        b = b - L*db

    Learning Rate:

        Tuning parameter in an optimization algorithm that determines the step size at ech iteration while moving towards a minimum of a loss function

    Derivatives 

        dw = ((Y_hat - Y)X)/m

        db = (Y_hat - Y)/m
