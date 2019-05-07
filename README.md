# Concrete Strength Analysis

A simple repository showing the use of a neural network for a regression task.

The dataset being analysed is located at https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength.

The framework being used for the machine learning is Keras.

The model has the following structure:

```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_41 (Dense)             (None, 50)                450       
_________________________________________________________________
dense_42 (Dense)             (None, 50)                2550      
_________________________________________________________________
dense_43 (Dense)             (None, 50)                2550      
_________________________________________________________________
dense_44 (Dense)             (None, 1)                 51        
=================================================================
Total params: 5,601
Trainable params: 5,601
Non-trainable params: 0
_________________________________________________________________
```
