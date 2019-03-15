# Single-Image Adversarial Depth Estimation Model

Keras implementation of the proposed single-image adversarial depth estimation model.


<p align="center">
  <b>Example 1<sup>[1]</sup></b>: <br>
  <img src="results/result1.gif" width="608">
</p>

<p align="center">
  <b>Example 2<sup>[1]</sup></b>: <br>
  <img src="results/result2.gif" width="608">
</p>

<sup>[1]</sup>(Input, Autoencoder, DenseNet)

## Requirements
The model is written and tested with Keras 2.2.0, Tensorflow 1.8.0 and Ubuntu 16.04. Matplotlib 2.2.2 is used for visualizing the various outputs.

## Training
The model was trained on the depth prediction split of the KITTI dataset (http://www.cvlibs.net/datasets/kitti/eval_depth.php?benchmark=depth_prediction). You can download the pre-trained models for each generator network in the links below:
* Autoencoder generator: TBD
* DenseNet generator: TBD


In-depth presentation of the proposed model at: https://www.dropbox.com/s/bmeg1yextjawl4b/Single_Image_Depth_Estimation_Using_Generative_Adversarial_Networks.pdf?dl=0 (Greek)
