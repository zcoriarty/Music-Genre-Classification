# Music-Genre-Classification
## Reason for the project
I have always enjoyed listening to music and one day I was curious about all of the different aspects that go into making music and as it turns out there is a TON. So, I thought it would be cool to see how good a neural network would be at classifying genres based entirely on various musical features, like chroma, crossing rate, and harmony. SPOILER: its quite good at it.

## Steps of the project
1. The data needed to be normalized for the network.
2. The labels were english categories(pop, rock, etc), so they needed a one-hot encoding for the neural network.
3. The data was fed into the deep neural network in batches of 32 where there were
4. The model was fit against a validation set and evaluated against a test set with an accuracy of >85%!

## Neural Network Specifics
- 4 layers all using the relu activation, except for the output layer which is linear
- Input dimension of 57 nodes, 1 output node
- Adam optimizer, MSE loss function
- 100 epochs, batch size of 32


