# Bigram Language Model

## Overview
This project focuses on building a Bigram Language Model using PyTorch. The model is trained to predict the next character in a sequence, enabling it to generate text based on the learned patterns from a given dataset. The project demonstrates various fundamental aspects of natural language processing (NLP) and deep learning.

## Project Structure
- **Data Preparation**: Loading and processing the text data.
- **Model Definition**: Creating a neural network for bigram language modeling.
- **Training**: Training the model using gradient descent and evaluating the loss.
- **Text Generation**: Generating new text based on the trained model.

## Technical Details

### Libraries Used
- **PyTorch**: For building and training the neural network.
- **Torch.nn**: For defining layers and operations in the model.
- **Torch.nn.functional**: For various activation functions and loss computation.

### Model Components
1. **Embedding Layer**: Converts input characters to dense vectors.
   ```python
   nn.Embedding(vocab_size, n_embed)

### Additional Details
To initialize GPU'S in Anaconda prompt follow the below steps:
Also install ipykernel to bring CUDA into the notebooks
**pip3 install ipykernel pylzma**
And we need buildtools for PyLZMA compression algorithm. 
![image](https://github.com/AkhilaKamma/LLM_GPT_Model_Scratch/assets/22701124/4061bde2-efcf-4337-9626-e911ceac16a5)
To install CUDA virtual environment in jupyter notebooks type the below command using anaconda prompt
 ```python
**python -m ipykernel install --user --name=cuda --display-name "cuda-gpt"**







