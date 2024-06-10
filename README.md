# Model Training Example on Jupyter

This example is for transfer-learning of a pre-trained model for object detection. In this example, we used pre-trained ResNet50, which we can easily download using Pytorch. It is assumed that the label data (a csv file) is providing pairs of folder name and the object in the images in the folder. Most of the time when train a model, we use images that contains only one object. The paths of the label and images need to be like this:
```
datasetname
├── train
│   ├── image1.jpeg
│   ├──  ...
│   └── imagen.jpeg
├── val
│   ├── image1.jpeg
│   ├──  ...
│   └── imagen.jpeg
├── test
│   ├── image1.jpeg
│   ├──  ...
│   └── imagen.jpeg
└── label.csv
```
