# Intel-Image-Classification
This is a Deep Learning Model to classify Images between 6 classes using CNN by Tensorflow and Keras.

The Link of dataset on Kaggle: [Intel Image Classificationd](https://www.kaggle.com/puneet6060/intel-image-classification).

The kernal on Kaggle: [Multi-Classification using CNN by Keras](https://www.kaggle.com/abdelrahmanzied/multi-classification-using-cnn-by-keras-val-acc88).




## Prerequisites
1. You should have python on your computer.
2. Install libraries:

    `pip install numpy`

    `pip install PIL`

    `pip install warnings`
    
    `pip install tensorlfow`
    
    If You want to install tensorflow GPU version you can check my article on Midium:

    [Install Tensorflow and Keras on GPU on Windows in 2021 using CUDA and cuDNN — All Errors are Fixed](https://abdelrahmanzied.medium.com/install-tensorflow-and-keras-on-gpu-on-windows-in-2021-using-cuda-and-cudnn-all-error-fixed-8a3967398eb7).

    If you have all prerequisites of tensorflow-gpu, just install using this command:

    `pip install --upgrade tensorflow-gpu==2.4.1`




## Usage
You can download the model "best_model.hdf5" file and import it using Tensorflow.

`Best_Model = tf.keras.models.load_model('best_model.hdf5')`




## GUI Version
GUI version is implemented in python using **tkinter** library.

### GUI Version Usage:
You can download the "GUI-Model.py" file and run it using python.
