# Recognize Digits Pattern in Loaded Images

This repository demonstrates a deep learning approach for recognising digit patterns from loaded images using **Keras**. The project applies a neural network workflow with **Batch Normalization** and **Dropout** to improve training stability, reduce overfitting, and support better generalisation.

Although this is an earlier machine learning project, it shows practical experience with image classification, model training, evaluation, and deep learning experimentation using Python-based tools.

## Project Purpose

The goal of this project is to classify digit patterns from image data and explore how neural network techniques can improve prediction performance.

This project demonstrates:

* Image-based machine learning
* Deep learning model development with Keras
* Digit recognition and classification
* Use of Batch Normalization for more stable training
* Use of Dropout for regularisation
* Model evaluation and prediction workflow
* Jupyter Notebook-based experimentation

## Key Features

* Loads image data for digit recognition
* Preprocesses image inputs for model training
* Builds a neural network model using Keras
* Applies Batch Normalization to improve learning stability
* Applies Dropout to reduce overfitting
* Trains and evaluates the model
* Tests predictions on loaded digit images
* Documents the model development workflow in notebook format

## Technologies Used

* Python 3
* Jupyter Notebook
* Keras
* TensorFlow
* NumPy
* Matplotlib
* scikit-learn, if used for evaluation or preprocessing

## Machine Learning Workflow

The project follows a typical image classification workflow:

1. Load digit image data
2. Preprocess and reshape image inputs
3. Normalise pixel values
4. Define the neural network architecture
5. Add Batch Normalization layers
6. Add Dropout layers for regularisation
7. Train the model
8. Evaluate model performance
9. Test predictions on loaded images
10. Review results and limitations

## Repository Structure

```text
Recognize-Digits-Pattern-in-Loaded-Images/
│
├── notebooks/              # Jupyter Notebook implementation
├── images/                 # Loaded digit images, if included
├── outputs/                # Prediction examples, charts, or screenshots
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies, if added
```

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Recognize-Digits-Pattern-in-Loaded-Images.git
cd Recognize-Digits-Pattern-in-Loaded-Images
```

Create and activate a virtual environment:

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run the cells step by step.

## Example Requirements File

If the repository does not already include a `requirements.txt`, you can add one with:

```text
tensorflow
keras
numpy
matplotlib
scikit-learn
jupyter
```

## Model Concepts Used

### Batch Normalization

Batch Normalization helps stabilise and speed up neural network training by normalising layer inputs during training. In this project, it supports more stable learning behaviour and can help the model converge more effectively.

### Dropout

Dropout is used as a regularisation technique to reduce overfitting. It randomly deactivates a portion of neurons during training, encouraging the model to learn more robust patterns instead of memorising the training data.

## Example Learning Outcomes

Through this project, I practised how to:

* Prepare image data for deep learning models
* Build a digit recognition model using Keras
* Apply Batch Normalization and Dropout in a neural network
* Train and evaluate an image classification model
* Test predictions on loaded images
* Interpret training behaviour and model performance
* Use notebooks for reproducible deep learning experimentation

## Relevance to My Current Career Direction

My current focus is cybersecurity GRC, cloud security, privacy governance, risk analytics, and AI assurance. This project supports that direction by demonstrating my foundation in AI model development, image classification, evaluation workflows, and Python-based experimentation.

These skills are relevant to modern security and governance work where AI systems need to be evaluated for reliability, accuracy, explainability, privacy risk, and responsible use.

## Future Improvements

Planned improvements for this repository include:

* Add clearer notebook explanations
* Add screenshots of prediction results
* Add training accuracy/loss visualisations
* Add confusion matrix and classification report
* Add more detailed model architecture documentation
* Add a cleaner `requirements.txt`
* Add sample loaded images for testing
* Add notes on model limitations and ethical considerations
* Extend the project with an AI assurance checklist for model evaluation

## Author

**Parisa Shojaei**

## Note

This is an earlier learning-focused deep learning project. It is being updated to better document the technical workflow, model concepts, and practical relevance of the implementation.
