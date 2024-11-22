# Machine Learning Model Training and Testing

This repository contains a machine learning pipeline for training and testing a model. The project consists of three main Python files: `train.py`, `model.py`, and `test_model.py`.

## Project Structure

- `model.py`: Contains the model architecture definition
- `train.py`: Handles the training pipeline and data processing
- `test_model.py`: Contains test cases for model validation

## Training the Model

To train the model, follow these steps:

1. Ensure you have all required dependencies installed:

```
pip install -r requirements.txt
```

2. Run the training script:

```
python src/train.py
```

This will train the model and save the best performing model to the `models` directory.

## Testing the Model

To test the model, follow these steps:

1. Run the test script:

```
python tests/test_model.py
``` 

This will run the test cases and ensure the model is performing as expected.