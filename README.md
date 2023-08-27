
# Waste-Management-CNN-Model
Deep Learning Image Classification Model based on Convolution Neural Network(CNN) Algorithm.


## Objective:
The world generates 2.01 billion tonnes of municipal solid waste annually, with at least 33 percent of that—extremely conservatively—not managed in an environmentally safe manner. Worldwide, waste generated per person per day averages 0.74 kilogram but ranges widely, from 0.11 to 4.54 kilograms. Though they only account for 16 percent of the world’s population, high-income countries generate about 34 percent, or 683 million tonnes, of the world’s waste.

When looking forward, global waste is expected to grow to 3.40 billion tonnes by 2050, more than double population growth over the same period.

Waste management or waste disposal includes the processes and actions required to manage waste from its inception to its final disposal. This includes the collection, transport, treatment, and disposal of waste, together with monitoring and regulation of the waste management process and waste-related laws, technologies, and economic mechanisms.

The __aim of waste management is to reduce the dangerous effects of such waste on the environment and human health.__ A big part of waste management deals with municipal solid waste, which is created by industrial, commercial, and household activity.

**The main objective of this project is build a Deep Learning Model, that can classify Organic(O) and Recycle(R) waste images effortlessly.**

## About Dataset:
This is a binary classification datatset of two classes: __Organic(O) and Recycle(R) waste images.__

**Organic(O):** Organic waste refers to any material that is biodegradable and comes from either a plant or an animal. E.g.: green waste, food waste, food-soiled paper, non-hazardous wood waste, green waste, and landscape and pruning waste.

**Recycle(R):** Recyclable wastes are the waste that can be processed and used again. E.g.: Iron and steel scrap, aluminum cans, glass bottles, paper, wood, and plastics etc.

* Total number of images in the dataset: 25077
* Total number of organic(O) waste images in the train directory: 12565
* Total number of recycle(R) waste images in the train directory: 9999
* Total number of organic(O) waste images in the validation directory: 1401
* Total number of recycle(R) waste images in the validation directory: 1112


## Algorithm:

Convolution Neural Network(CNN) is a type of Deep Learning neural network architecture commonly used in Computer Vision. CNNs are inspired by the way the visual cortex works in the human brain.

CNNs consist of a series of layers, each of which performs a specific task. The first layer is the convolutional layer, which applies filters to the input image to extract features. The filters are small, 2D arrays of weights that are learned during the training process. The convolutional layer produces a set of feature maps, each of which represents a different feature of the image.

The next layer is the pooling layer, which downsamples the feature maps to reduce the amount of computation required. The pooling layer can be either max pooling or average pooling. Max pooling takes the maximum value from each region of the feature map, while average pooling takes the average value.

The final layer is the fully connected layer, which is a traditional neural network layer that makes the final prediction. The fully connected layer takes the output from the pooling layer and connects it to a set of output neurons, one for each possible class.
## Language and library:

Language: Python 3.11.4

Library: TensorFlow and Matplotlib
