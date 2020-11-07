# Handwritten Digit Classification
 Downloading the MNIST handwritten digit dataset. It contains 28X28 images. Flatten them into 784-dimensional binary vectors. Keeping aside 20% data for testing and another 20% for validation. <br />     
  <br />
 Now, draw a random subset of 10 dimensions (out of 784). Based on these 10 dimensions only, build a decision tree (using library function). Maximum depth :5. Calculating accuracy of the tree on validation set. <br />                    
 <br />
 Repeating this process for 50 random subsets like this, each of dimension 10.For each of them, built a decision tree of max. depth 5. Calculating accuracy on validation set. <br />
 <br />
Carrying out weighted classification of the test set using these 50 decision trees, along with their validation accuracies as weights. Reporting the accuracy. <br />
 <br />
5) Starting with this ensemble as the initial classifier, implementing Adaboost algorithm. At each stage, built a decision tree using entropy based on weighted examples as the heterogeneity measure of each node. Each tree will have maximum depth of 5. Maximum 20 iterations used for Adaboost. <br />    
 <br />
Using this ensemble, carrying out classification on the test set and reporting accuracy <br />
