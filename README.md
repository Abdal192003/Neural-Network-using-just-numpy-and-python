  

# Neural Network using just Numpy & Python

  

Given-
- no. of input node - 784
- no. of hidden node - 100  (for training purpose , MNIST data set the researcher has taken 100 as it gives good accuracy suggested by the researcher.)
- no. of output node - 10  (Because in MNIST handwritten data set it only has 10 label numbers )
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Using the probability normal distribution function to initialise the   weights of input_hidden and output_hidden.
- Using Sigmoid Activation Function to as it has smooth curve and it is widely implemented.
- And in neural network learning is done through weights , so to update the weights we have formula.
  ![1_2wULsk4M4HG12bZ5cB-bPA](https://github.com/user-attachments/assets/96681453-6801-45b9-bc19-6d561f167e2b)
- And we have training data set of 100 length and testing data set of 10 len. Given epoch-2 so it will train the data twice and while querying we are getting good result .
- The output_node with the most value gives the correct results as it is giving [0.96681712] value for label (1).
- Giving an overall accuracy of 70% .





![Screenshot 2024-07-22 204339](https://github.com/user-attachments/assets/c9190028-5503-462c-a87d-6e70925b48cd)
![Screenshot 2024-07-22 204358](https://github.com/user-attachments/assets/9c5f16cc-6528-4669-bc0a-5a39201f1cea)
![Screenshot 2024-07-22 204408](https://github.com/user-attachments/assets/69d15ad5-2be8-40f0-b935-7c4a75167201)
