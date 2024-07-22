# Cats vs. Dogs Classification

## Project Overview
This project builds a deep learning model to classify images of cats and dogs using Convolutional Neural Networks (CNNs).

## Dataset
The dataset is sourced from Kaggle and contains labeled images of cats and dogs. Download it [here](https://www.kaggle.com/datasets/salader/dogs-vs-cats/data).

## Prerequisites
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/ChandanaAasrithaPentakota/Cats-vs.-Dogs-Classification.git
    cd Cats-vs.-Dogs-Classification
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/salader/dogs-vs-cats/data) and place it in the `data/` directory.
2. Run the training script:
    ```bash
    python train.py
    ```
3. Evaluate the model:
    ```bash
    python evaluate.py
    ```

## Accuracy
The model was trained for 15 epochs with the following results:
- **Initial Accuracy**: 57.20%
- **Final Training Accuracy**: 97.58%
- **Final Validation Accuracy**: 88.34%

Below is a summary of the training process:

| Epoch | Training Accuracy | Validation Accuracy |
|-------|--------------------|---------------------|
| 1     | 57.20%             | 64.22%              |
| 5     | 87.88%             | 87.36%              |
| 10    | 95.42%             | 89.42%              |
| 15    | 97.58%             | 88.34%              |

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, please contact [chandanaaasritha@gmail.com](mailto:chandanaaasritha@gmail.com).
