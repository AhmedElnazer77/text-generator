# text-generator
# Text Generation Model
This code represents a text generation model based on a recurrent neural network (RNN) with GRU (Gated Recurrent Unit) layers. The model is trained on the "Harry Potter" book series.
# Requirements
- Python 3.9
- TensorFlow (version 2.14.0)
- Transformers library (version 4.35.0)
- Other dependencies (specified in requirements.txt)

# Installation
1. Clone the repository:
    
    **git clone https://github.com/your_username/text-generation-model.git**

   
2. Navigate to the project directory:
   
   **cd text-generation-model**

3. Install the dependencies:

     **pip install -r requirements.txt**


# Dataset Preparation
- The code reads multiple text files representing different books from the "Harry Potter" series.
- The contents of these files are concatenated and saved as a single text file named "harrypotter.txt".
- The script then reads the contents of "harrypotter.txt" and performs some initial data preprocessing.


# Model Usage
- After training, the model weights are loaded from the latest checkpoint.
- The generate_text function is used to generate new text based on a given starting string.
- The function generates a specified number of characters by sampling from the model's predictions.
- The generated text is returned as output.



# Usage
1. Make sure you have the required version of TensorFlow installed.
2. Execute the code to train the model and generate text.
