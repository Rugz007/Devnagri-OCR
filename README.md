# Devanagri OCR
Optical Character Recognition for Devnagri Characters using Tensorflow 2.

We have used our own custom CNN model architecture to get an accuracy of 96.63% on the test set.

Link of the dataset: [**Devanagari Handwritten Character Data Set**](https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset)

## Training Results

### Loss Plot
![Loss vs accuracy graph](https://i.imgur.com/AROexoW.png)
### Accuracy Plot
![accuracy graph](https://i.imgur.com/0yPggVb.png)


Model Training after epoch 18

    Epoch 18/20
    1100/1100 [==============================] - 25s 22ms/step - loss: 0.2892 - accuracy: 0.9767 - val_loss: 0.5923 - val_accuracy: 0.9036
    Epoch 19/20
    1100/1100 [==============================] - 25s 22ms/step - loss: 0.2757 - accuracy: 0.9776 - val_loss: 0.7176 - val_accuracy: 0.8881
    Epoch 20/20
    1100/1100 [==============================] - 25s 22ms/step - loss: 0.2739 - accuracy: 0.9772 - val_loss: 0.5926 - val_accuracy: 0.8991


## Prerequisites

- Python 3.7
- [Tensorflow 2.5.x](https://github.com/tensorflow/tensorflow/)
- [NumPy](http://www.numpy.org/)
- [PIL](https://pillow.readthedocs.io/en/stable/)
- [Matplotlib](https://matplotlib.org/)
<br>Clone this repo.
 
```bash
   git clone https://github.com/Rugz007/Devnagri-OCR.git
``` 

Python in your machine should be 3.7.x.<br>
Install Jupyter Notebook.<br>
```bash
   pip install jupyter-notebook
```


