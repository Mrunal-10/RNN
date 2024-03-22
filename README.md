What's Inside?
1. Importing Libraries and Data
We start by importing essential libraries from TensorFlow and Keras. The IMDb movie review dataset is loaded, containing reviews labeled as positive or negative. We restrict the vocabulary size to the 5000 most occurring words to manage computational complexity.

2. Data Preprocessing
The raw text data is converted into numerical sequences suitable for input to the neural network. We pad sequences to ensure uniform length, truncating or padding as necessary to a maximum length of 400 words.

3. Building the RNN Model
You'll learn how to construct a simple RNN model for sentiment analysis. The model comprises an Embedding layer, a SimpleRNN layer, and a Dense layer for binary classification. The model architecture and summary are presented, providing insights into the network's structure.

4. Compiling and Training the Model
With the model defined, it's time to compile it by specifying the loss function, optimizer, and evaluation metrics. The model is then trained on the training dataset, with validation performance monitored to prevent overfitting.

5. Evaluating Model Performance
After training, you'll evaluate the model's performance on the test dataset to assess its accuracy in classifying unseen reviews as positive or negative. The model's score on the test data is reported, providing an indication of its real-world performance.

How to Get Started?
Access the Notebook: Click on the provided link or download the notebook (RNN.ipynb) to your local machine.

Set Up the Environment: Ensure you have TensorFlow and Keras installed in your Python environment. 
![image](https://github.com/Mrunal-10/RNN/assets/83581750/2d14e6c4-30e4-4b0c-aafd-f5c81f3ea591)
![image](https://github.com/Mrunal-10/RNN/assets/83581750/a098d938-ad3e-4da3-96f3-eee0ae2bb836)
![image](https://github.com/Mrunal-10/RNN/assets/83581750/789e97d1-ce73-4252-98b7-9c49b254f1e8)
![image](https://github.com/Mrunal-10/RNN/assets/83581750/2b99574f-6793-4ac2-81cf-172d294abc48)
