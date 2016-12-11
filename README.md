# Photography-classification-in-aesthetics
Deep learning application in aesthetic analysis of potographic images

Run code instructions

All the code can be runned in ipython notebook “Photography classification in aesthetics.ipynb”. just follow the final report contents, you will be able to run all the code and get the results. 
Note that there are data files need to put at same directory with .ipynb file. You should download all source files in the below links.

datafiles links:
vgg weights(vgg16_weights.h5):
url: https://drive.google.com/file/d/0Bz7KyqmuGsilT0J5dmRCM0ROVHc/view

dataset url: https://drive.google.com/open?id=0B4IRvXQLN6BtTkN3YW9BSDgxUXM

1. dataset.zip is used for color histogram and VGG

2. dataset4.zip is used for triplet loss

Potential sources:

The details of reference are in the final report, here is summary of potential sources.

1. crop_and_scale_image function and fnames_to_labels functions are referred from PDS homework.
2. The codes using tensorflow to implement CNN was referred from https://www.tensorflow.org/versions/r0.11/tutorials/mnist/pros/index.html
3. Codes for VGG16 method was referred from VGG website https://gist.github.com/baraldilorenzo/07d7802847aaad0a35d3
