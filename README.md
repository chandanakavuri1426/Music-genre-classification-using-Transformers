# Music-genre-classification-using-Transformers
In our research, we fine-tuned the DistilHuBERT model using the GTZAN dataset for music genre classification. We evaluated the effectiveness of three different data augmentation techniques.

Introduction: This repository contains code for a music genre classification project using machine learning techniques. The project aims to classify audio clips into various music genres, providing a valuable tool for music enthusiasts, streaming platforms, and researchers.

Project Structure:

data/: This directory contains the GTZAN dataset, which comprises audio clips from ten different music genres.
models/: This directory contains pre-trained models and fine-tuned models used for audio classification.
utils/: This directory contains utility functions for data preprocessing, model evaluation, and visualization.
train.py: This script is used to train and fine-tune the classification model on the GTZAN dataset.
evaluate.py: This script is used to evaluate the performance of the trained model on a separate test set.
predict.py: This script allows users to classify audio files using a trained model.
Getting Started:

Clone the repository to your local machine: git clone <repository-url>
Install the required dependencies: pip install -r requirements.txt
Download the GTZAN dataset and place it in the data/ directory.
Train the classification model using the train.py script.
Evaluate the model's performance using the evaluate.py script.
Use the predict.py script to classify audio files.
Usage:

train.py: Run python train.py to train the classification model. Adjust the training parameters as needed in the script.
evaluate.py: Run python evaluate.py to evaluate the trained model on the test set.
predict.py: Run python predict.py <audio-file> to classify a single audio file using the trained model.
Contributing: Contributions to this project are welcome. If you encounter any bugs or have suggestions for improvements, please open an issue or submit a pull request on GitHub.

Acknowledgments:

The GTZAN dataset used in this project was originally created by George Tzanetakis and Perry Cook and is widely used for music genre classification research.
We would like to thank the creators of the Hugging Face Transformers library for providing pre-trained models and tools for natural language processing and audio classification tasks.
