# Style-Transfer-Keras

This Style Transfer implementation is based on the paper of Gatys' : [Image Style Transfer Using Convolutional Neural Networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)

The implementation used Keras and Tensorflow API.

Compare to the Gatys' paper, there are 3 main differences:
- the adam optimizer is used insteand of BFGS
- the total variance loss is also used (which was not present in the paper)
- The convolution layers used come from VGG16 instead of VGG19

