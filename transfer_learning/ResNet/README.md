# Transfer Learning
Transfer learning refers to the technique of using knowledge of one domain to another domain.i.e. a NN model trained on one dataset can be used for other dataset by fine-tuning the former network.

## Re-train ResNet50 model on new data
This repository shows how we can use transfer learning in keras with the example of training a 4 class classification model using  Resnet50 pre-trained weights. Resnet50 is the CNN models trained on more than a million images of 1000 different categories. It has 50 layers. 

### Dependecy
It requires following dependency to be installed:
- Kearas
- Matplotlib
- numpy
- sklearn

## How to use
- Download or clone the repository
- Extract the data.zip, it contains the data/classes/images of four different classes
- You can re-train ResNet on your on dataset. Just replace data/classes/ with your images
- Open the ResNet50_retrain.ipynb in Jupyter notebook
- Excute all the cells one by one
- ResNet50_retrain.ipynb and data folder should be in the same directory

## Simply use the ResNet50 model
- If you do not want to re-train the model on custom data, instead just want to test the ResNet50 model, then
- Simply open ResNet50_test.ipynb in Jupyter notebook and excute the cells
- Notebook uses elephant.jpg as input to the model

### References:
The code is inspired from the following repository and edited as per the requirement
- https://github.com/fchollet/deep-learning-models
- https://github.com/anujshah1003/Transfer-Learning-in-keras---custom-data


A good explanation of how to use transfer learning practically is explained in http://cs231n.github.io/transfer-learning/
