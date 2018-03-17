# TODO
## Part A
1. Read csv files into Pandas dataframe
    - Concatenate all the data
2. Write the function defined in the paper that maps radar daily data to predicted weekly rainfall
3. Using this function, generate a mapping of rain gauge data to (x,y) that minimizes the loss between actual and predicted
4. Examine this mapping. If there are collisions, may need to run matching algorithm to ensure distinctness

## Part B
1. Generate labeled data (3d, convolutional window by time)
    - Window size is hyperparameter, has to be odd, should be small (3x3 possible)
    - Time is a hyperparameter, because whole dataset is too big, limit to past few days
1. Using labeled data (50), learn parameters of the given function and see total loss
2. Design and train NN with recurrent neurons
3. See if results are better

## Part C
1. Write paper (lol)