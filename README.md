# SimpleCNN
Deep learning project for pet image segmentation using trimap masks and Keras.
# 🐶🐱 Oxford Pets Image Segmentation with Keras

This project demonstrates semantic image segmentation using the [Oxford-IIIT Pet Dataset](http://www.robots.ox.ac.uk/~vgg/data/pets/), implemented with TensorFlow and Keras. The goal is to classify each pixel in an image as either background, cat, or dog using a lightweight encoder–decoder architecture.

## 📁 Dataset

The dataset contains:
- **Images** of 37 pet breeds (cats and dogs)
- **Trimap annotations** labeling each pixel as foreground (pet), background, or outline

Download the dataset manually or via script:
```bash
wget http://www.robots.ox.ac.uk/~vgg/data/pets/data/images.tar.gz
wget http://www.robots.ox.ac.uk/~vgg/data/pets/data/annotations.tar.gz
tar -xf images.tar.gz
tar -xf annotations.tar.gz
