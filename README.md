# Wheat Head Detection using Computer Vision
![image](https://github.com/zain-ramzan/Wheat-Head-Detection-using-Computer-Vision/assets/64620737/fddc14de-be72-40fc-b18d-919a7538dd49)
### Global Wheat Head Dataset
The [Global Wheat Head Dataset](https://www.global-wheat.com/) is a collection of images designed to support the development of accurate wheat head detection models for 
applications in wheat phenotyping and crop management. Wheat heads, also known as spikes, are the grain-bearing parts of the wheat plant. 
Accurate estimation of wheat head density and size is essential for assessing crop health, maturity, and yield potential. The dataset, 
created by a collaboration of nine research institutes from seven countries, covers multiple growing regions to ensure models generalize well across different environments.

### Key Features
* The dataset contains over 3,000 training images from Europe (France, UK, Switzerland) and North America (Canada).
* It includes approximately 1,000 test images from Australia, Japan, and China.
* Images are outdoor field images, capturing the natural variability in wheat head appearances.
* Annotations include wheat head bounding boxes to support object detection tasks.
### Dataset Structure
The Global Wheat Head Dataset is organized into two main subsets:
* **Training Set:** This subset contains over 3,000 images from Europe and North America. The images are labeled with wheat head bounding boxes, 
providing ground truth for training object detection models.
* **Test Set:** This subset consists of approximately 1,000 images from Australia, Japan, and China. These images are used for evaluating the performance 
of trained models on unseen genotypes, environments, and observational conditions.
### Applications
The Global Wheat Head Dataset is widely used for training and evaluating deep learning models in wheat head detection tasks. The dataset's diverse 
set of images, capturing a wide range of appearances, environments, and conditions, make it a valuable resource for researchers and practitioners 
in the field of plant phenotyping and crop management.

### Dataset YAML
A YAML (Yet Another Markup Language) file is used to define the dataset configuration. It contains information about the dataset's paths, classes, 
and other relevant information.
### Usage
To train a YOLOv8n model on the Global Wheat Head Dataset for 100 epochs with an image size of 640, you can use the following code snippets. 
For a comprehensive list of available arguments, refer to the model Training page.
### Sample Data and Annotations
The Global Wheat Head Dataset contains a diverse set of outdoor field images, capturing the natural variability in wheat head appearances, 
environments, and conditions. Here are some examples of data from the dataset, along with their corresponding annotation you can see in the above picture.

**Wheat Head Detection:** This image demonstrates an example of wheat head detection, where wheat heads are annotated with bounding boxes. The dataset provides 
a variety of images to facilitate the development of models for this task.
The example showcases the variety and complexity of the data in the Global Wheat Head Dataset and highlights the importance of accurate wheat head detection for applications in wheat **Phenotyping** and **Crop Management**.
