# Toxic-Comment-Detection-using-Deep-Learning-in-Python


Workflow
1. Data Preprocessing:

Loading Data: The notebook starts with loading the dataset containing comments and their corresponding toxicity labels.
Text Cleaning: The comments are preprocessed to remove unwanted characters, convert text to lowercase, and perform other text cleaning steps.
Tokenization: The text data is tokenized and converted into sequences that can be fed into the model.

2. Model Building:

Model Architecture: The notebook defines a neural network model architecture. It likely includes embedding layers, LSTM/GRU layers, and dense layers to capture the features of the text data.
Compilation: The model is compiled with appropriate loss functions and optimizers, tailored for binary classification tasks.

3. Model Training:

Training Setup: The model is trained on the preprocessed dataset. Training parameters such as batch size, number of epochs, and validation split are defined.
Training Process: The model is trained, and performance metrics are recorded to monitor its progress.

4. Model Evaluation:

Performance Metrics: The notebook evaluates the model's performance using metrics like accuracy, precision, recall, and F1-score on the validation/test dataset.
Error Analysis: It includes an analysis of the errors to understand the model's weaknesses and potential areas for improvement.

5. Deployment:

Gradio Interface: A Gradio interface is created to allow users to input comments and receive toxicity scores in real time.
Launching Interface: The interface is launched, providing a public URL for users to access the model and test its performance.


