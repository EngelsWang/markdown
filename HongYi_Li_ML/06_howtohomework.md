# framework ML
![](img/framework.PNG)
![](img/guild.PNG)

## model bias

## optimization issue

![](img/optimis.PNG)

## 正确认识overfitting

Flexible model

1. Data augmentation
2. contrained model
   
    fully-connected  && CNN 

    ![](img/contrainedmodel.PNG) 

## crossvalidation

![](img/crossvalidation.PNG)    

N-fold Cross Validation

![](img/nfold.PNG)

### mismatch


# when gradient decent is small

# local minima && saddle point

critical point

Tayler Series Approximation

Hessian

![](img/Tayler.PNG)

![](img/Hessian.PNG)

H may tell us paramiter update direction!

![](img/h.PNG)

高维local minima 很少

# Batch

1 epoch = see all the batches once

small batch v.s. large batch

![](img/update.PNG)

![](img/batch&acc.PNG)

small batch is better on testing data

Flat Minima && Sharp Minima

![](img/LB&&SB.PNG)

# Momentum

Gradient Descent + Momentum

![](img/GD+M.PNG)

# Training can be difficult even without critical point
## different parameters needs different learning rate

### root mean square

![](img/rms_lr.PNG)
## Learning rate adapts dynamincally

### RMSProp
![](img/RMSProp.PNG) 

Adam : RMSProp + Momentum

## Learning Rate Scheduling
Learning Rate Decay

Warm Up

![](img/optim_sum.PNG)

# Batch Normalization
## Changing Landscape
![](img/CL.PNG) 
## Feature Normalization
standard deviation
## Batch Normalization
![](img/bn.PNG)
Testing

moving average

![](img/ma.PNG)

Internal Covariate Shift?

change erroe surface