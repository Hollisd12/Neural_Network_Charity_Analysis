# Neural_Network_Charity_Analysis

## Overview
In this project, we perform an analysis for Alphabet Soup to help determine which organizations will be successful if they receive funding. We use a deep learning neural network model on our dataset to determine if the money will be used effectively or misused by the organization. This will help Alphabet Soup determine where to invest their money to have the highest possible impact.

## Results

### First iteration
The first iteration of the model included 110 neurons with 80 in the firts hidden layer and 30 in the second hidden layer.

The goal was to achieve 75% accuracy. The first iteration of the neural network came close at 72.49% with a loss of 56.17%

### First optimization
The first attempt at optimization was to remove any noisy data. The status column was removed and then the model was run with the new data.

This resulted in an accuracy of 74.19% and a loss of 53.12%, a slight increase of accuracy and decrease in loss from the first iteration.

### Second optimization
The second change made to the model was increasing the number of neurons in the hidden layers. They were changed from 80, 30 to 120 for the first layer and 60 for the second layer.

This iteration resulted in an accuracy of 74.27% and a loss of 53.24% which increased slightly in accuracy from the previous optimization but also an increase in loss.

### Third optimization
The third iteration of the neural netowrk involved adding a third hidden layer with 60 nodes and changing the activation function for the second hidden layer from relu to sigmoid.

This iteration resulted in a 74.21% accuracy and 53.06% loss. This was a slightly lowered accuracy score from the previous model and a slightly lower loss.

##Summary
After three attempts at optimization, we were unable to reach the desired goal of 75% accuracy. The loss is also high for all of the model iterations. Seeing that adding a third hidden layer and changing the activation functions resulted in the best outcome it could be determined that continuing to fine tune the layers one at a time an accuracy of 75% could most likely be achieved by adding one or two more layers. Also, changing to include more sigmoid activation functions in the hidden layers could possibly increase the accuracy. The sigmoid function acts closer to a classification system and may help the model.
