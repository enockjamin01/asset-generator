# Asset Generator
Assets Generator is a project that is built using DCGAN architecture, to generate Game assets for 2D games. This is built using TensorFlow and Keras. The model can take a noise image of (1,1,128) for n numbers and can generate n numbers of images of (64,64,3).

This model is trained with 865 images for 150 epochs with a batch of 32 

#### Training time: 4 hours
#### Notebook setting: TPU

### Note:
This project has the complete code base but is trained for a very short time period. Due to computation restrictions.

The code for Data Augmentation is commented on the code cell and you can change the number of epochs and batch size and train for more epochs for better results and Experimenting with the project

#### There is no change required in tunning the model code

## Input shape:
### Noise: (1,1,128)

## Adding more training data

More data can be added to the respective image folder and the path should be provided to the respective image writing and getting functions (write_images,getimages)

## Frameworks used:

   ```bash
python3 -m pip install TensorFlow

pip install opencv-python

pip install matplotlib

pip install numpy
```
