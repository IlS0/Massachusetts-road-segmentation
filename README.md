# Massachusetts-road-segmentation

Training a Convolutional Neural Network to segment Massachusetts roads from aerial imagery. The model is made using __PytTorch__ framework. Final metric-value (IoU) is about 88%. To have more information, see the [thesis](https://www.cs.toronto.edu/~vmnih/docs/Mnih_Volodymyr_PhD_Thesis.pdf).

## Files description

1. `main.ipynb`: the notebook with CNN model training and testing;
2. `scripts/cleaner.py`: the script that fixes defective labels in the dataset;
3. `scripts/cropper.py`: the script that cuts all images into 255x255 pieces.

The scripts were made by [JooudDoo](https://github.com/JooudDoo/AI_Tasks/tree/master/02_Task/Scripts).

## Build

### Cloning

Clone the repository from github by running the command in the terminal:
`git clone https://github.com/IlS0/Massachusetts-road-segmentation.git`.

### Requirements

Unzip the archive, navigate to the directory and install the requirements by running the following command:
`pip install -r requirements.txt`.

### Downloading the dataset

[Download](https://www.kaggle.com/datasets/balraj98/massachusetts-roads-dataset) the dataset containing 1171 aerial images of the state of Massachusetts.

## Run

To run the notebook, the `main.ipynb` file and the dataset must be in the same directory. Also make sure you have Jupyter Notebook installed. You can see the installation guide [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html#installing-jupyter-using-anaconda-and-conda). 

