# Image segmentation from a classifier

Images can be segmented using a pretrained CNN classification network. It is not a good idea for segmentation, but it is a very effective tool for visualization of the classifier.

![GitHub Logo](/images/segemented_images.jpg)


The logic behind this is very simple, Gradient in the image space signifies the contribution of each pixel toward prediction and this information can be used for image segmentation.

## Corresponding Medium Post
https://medium.com/@negidhirendersingh26/image-segmentation-using-classifier-82f2085f5bc6

## Demo
[Ipython notebook](image_segmentation.ipynb)

## References
[Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps](https://arxiv.org/abs/1312.6034)


## License
The Apache License 2.0. Please see the [license file](LICENSE) for more informat
