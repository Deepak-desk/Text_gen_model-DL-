# Text Generation Model

This repository contains a text generation model built using TensorFlow and trained on the Tiny Shakespeare dataset. The model uses an LSTM-based architecture to generate text based on the input sequence.

## Features
- Preprocessing of the Tiny Shakespeare dataset
- LSTM-based text generation model
- Checkpointing for saving and loading model weights
- Text generation with a customizable starting string

## Files
- `model_00.ipynb`: Jupyter Notebook containing the code for training and generating text.
- `train.csv`, `test.csv`, `validation.csv`: Placeholder files for potential dataset splits.

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the `model_00.ipynb` notebook in Jupyter or VS Code.
3. Run the cells to train the model and generate text.

## Requirements
- Python 3.8+
- TensorFlow
- TensorFlow Datasets
- NumPy

Install the required packages using pip:
```bash
pip install tensorflow tensorflow-datasets numpy
```

## Example
Generate text with the model:
```python
print(generate_text(model, start_string="QUEEN: So, lets end this"))
```

## License
This project is licensed under the MIT License.

## NOTE:
increase the epoch for better understanding for model to get correct output
