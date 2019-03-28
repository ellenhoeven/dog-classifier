# dog-classifier

This project is part of Udacity's deep learning nanodegree program. It uses Pytorch to implement a CNN which recognizes whether an image contains a dog or a human. If the image contains a dog, it can detect the dog breed. It does so by using a transfer learning approach based on VGG16 and Resnet50.

# Get started
```
git clone https://github.com/ellenhoeven/dog-classifier/
cd dog-classifier
```
Create and activate environment
```
conda create -n <envname> python=3.6 numpy matplotlib pil jupyter pytorch
conda install -c conda-forge opencv
```
# Running the model
- Run model from within the notebook, run: `jupyter notebook`
- Add some more images for testing purpose to image folder if needed
