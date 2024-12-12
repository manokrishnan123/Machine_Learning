# Long Short-Term Memory(LSTM) Model
 Long Short-Term Memory Networks are a type of RNN specialised for sequential data, overcoming and vanishing the gradient problem. LSTMs enable deep learning models to retain long-term dependencies, crucial for tasks like language modeling and time-series analysis.

This repository contains a powerpoint slide explaining the model and architecture of LSTM model and a LSTM Tutorial .ipynb file which illustrates a text prediction with LSTM model.

The detailed description of the LSTM prediction model and the steps to access the ipynb file and run the code is given below.

# Description

This project involves tokenizing input text, generating sequences, padding sequences, building and training an LSTM model, and finally predicting the next word based on the already trained model.

# LSTM Text Prediction
1. Data Collection - The dataset used is the text of Shakespeare’s Hamlet. This text offers a rich and complex language structure, providing an ideal challenge for training a predictive model.

2. Data Preprocessing
    a. The text is tokenized to convert words into numerical indices.
    b. Sequences of fixed length are created and padded to ensure uniform input sizes.
    c. The prepared sequences are split into training and testing datasets for model development and evaluation.

3. Model Building - The LSTM model is constructed with the following components:
    a. An embedding layer for learning word representations.
    b. Two LSTM layers to capture long-term dependencies in the text.
    c. A dense output layer with softmax activation to predict the probability distribution of the next word.

4. Model Training
    a. The model is trained on the prepared sequences.
    b. Early stopping is implemented to monitor validation loss and halt training if the model stops improving. This prevents overfitting and ensures optimal performance.

5. Model Evaluation - The trained model is tested on example sentences to assess its ability to accurately predict the next word. This evaluation demonstrates the model’s understanding of the patterns in the text.

# Model Architecture
The LSTM model is one version of a RNN, usually applied when dealing with sequential data. It's especially effective for picking out the long-range dependencies and patterns across text. The model architecture will involve an embedding layer, LSTM layers, and, finally, a dense layer that would give a prediction.

# Technologies/Tools Used
1. Tensorflow
2. Jupyter Notebook

# How to use

1. Ensure that the requirements.txt file and the LSTM Tutorial file is saved in the same location.
2. Run the LSTM Tutorial.ipynb file using Jupyter Notebook, VS Code or any other IDE's that can interact with .ipynb files.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
