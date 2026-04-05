# linear_regression_from_scratch

**Linear Regression**

**Y=wX + b**

Y --> Dependent Veriable

X --> Independent Veriable

w --> weight

b --> Bias

**Gradient Dencent:**

Gredient Descent is an optimization algorithem used for minimizing the loss functin in verious machine learning algorithems it is used for updating the parameters of the learning model

w = w - a*dw

b = b - a*db

**Learning Rate:**

Learning rate is a tuining parameter in an optimization algorithem that determines the step size at each iteration while moving toward of a loss function


<img width="428" height="235" alt="Screenshot 2026-04-05 170252" src="https://github.com/user-attachments/assets/b2a43db7-ec54-4142-a86b-37c9908ab45c" />




Work flow of the Linear Regression model:

Step 1: Set Learning Rate & Number of Iterations; Initiate Random weight and bias value.

Step 2: Build Linear Regression Equation. (y = wx + b)

Step 3: Find the "y pred" value for given x value for the corresponding weight & bias.

Step 4: Check the loss function for these parameter values. ( difference between "y pred" & "true y")

Step 5: Update the parameter values using Gradient Descent. (new weight & bias value)

Step 6: Step 3, 4, 5 are repeated till we get minimum loss function

Finally we will get the best model (best weight and bias value) as it has minimum loss function.
