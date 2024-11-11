# Fashion Detection: Classification
The Fashion Classification project aims to classify different types of clothing items in images using a convolutional neural network (CNN). This project is highly applicable in e-commerce, where accurate classification of clothing can improve search, recommendation, and cataloging features. 

<p align="center">
  <br>
  <img src="results.gif" alt="pic" width="500">
  <br>
</p>
<p align="center" >
  <a href="#objective">Objective</a> •
  <a href="#dataset">Dataset</a> •
  <a href="#model-architecture">Model Architecture</a> •
  <a href="#contributors">Contributors</a>
</p>

### Objective
The primary objective is to develop a neural network model capable of classifying various clothing items (e.g., t-shirts, pants, dresses) based on their visual characteristics. Unlike object detection models that require localization, this model focuses solely on classifying the type of clothing in a full image, independent of the item’s position.

### Dataset
The project utilizes the [**Colorful Fashion Dataset For Object Detection**]((https://www.kaggle.com/datasets/nguyngiabol/colorful-fashion-dataset-for-object-detection)) available on Kaggle. Although this dataset contains bounding box annotations, these are not used in this project, as the focus is on classification rather than object detection. Instead, each full image is processed and labeled according to the type of clothing it contains.

### Model Architecture
The model is based on a Convolutional Neural Network (CNN) designed for image classification tasks. The architecture includes:
- **Convolutional Layers**: For extracting visual features from images.
- **Pooling Layers**: For down-sampling, reducing spatial dimensions while retaining essential features.
- **Fully Connected Layers**: For learning complex patterns and producing classification outputs.
- **Output Layer**: Using a softmax activation to produce probabilities for each clothing class.


## Contributors
[@Mendezg1](https://github.com/Mendezg1) | [@MelissaPerez09](https://github.com/MelissaPerez09) | [@bl33h](https://github.com/bl33h)
