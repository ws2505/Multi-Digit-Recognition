# SVHNClassifier

This project uses TensorFlow to implement [Multi-digit Number Recognition from Street View Imagery using Deep Convolutional Neural Networks](http://arxiv.org/pdf/1312.6082.pdf) 


## Results
![image](Multi-DigitRecognition/image/res.png)
## Accuracy

* Best accuracy: 0.936



## Requirements

* Python 3
* Tensorflow
* h5py


## Setup

1. Clone the source code

2. Download [SVHN Dataset](http://ufldl.stanford.edu/housenumbers/) format 1

3. Extract to data folder


## Usage

1. Process the data, convert data to TFRecords format

    ```
    Open `dataprocess.ipynb` in Jupyter
    ```


2. Training Process

    ```
    Open `Train.ipynb` in Jupyter
    ```


3. Evaluate the Result

    ```
    Open `Test.ipynb` in Jupyter
    ```

