# Human Segmentation with PyTorch

## Introduction
This project focuses on segmenting humans in images using deep learning. It utilizes PyTorch and other libraries to train a model capable of distinguishing between human and non-human elements in a photograph.

## Technologies
- Python
- PyTorch
- OpenCV
- Pandas
- NumPy
- Matplotlib
- Albumentations for data augmentation
- segmentation-models-pytorch library

## Setup
To run this project, install the required libraries by running the following commands:

```bash
pip install segmentation-models-pytorch
pip install -U git+https://github.com/albumentations-team/albumentations
pip install --upgrade opencv-contrib-python
```

Clone the dataset repository (Original Dataset author):

```bash
git clone https://github.com/VikramShenoy97/Human-Segmentation-Dataset.git
```

## Usage
To use this project, follow these steps:
1. Ensure all dependencies are installed as mentioned in the setup section.
2. Load the Jupyter notebook and execute the cells sequentially.
3. The notebook includes sections for data preparation, model training, and evaluation.

## Project Structure
- Data Preparation: Download the dataset and prepare it for training and validation.
- Model Training: Define and train the segmentation model using the prepared data.
- Evaluation: Evaluate the model's performance on the validation set.

## Contributing
Feel free to fork this project and contribute by submitting a pull request.

## License
[MIT](https://choosealicense.com/licenses/mit/)