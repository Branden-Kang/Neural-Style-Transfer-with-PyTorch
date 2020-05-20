# Neural-Style-Transfer-with-PyTorch

## What is neural style transfer?
Neural style transfer is a technique used to generate images in the style of another image. The neural-style algorithm takes a content-image as input, a style image, and returns the content image as if it were painted using the artistic style of the style image.

## Import packages:
- torch, torch.nn, numpy: implementing the neural network and scientific computation respectively.
- torch.optim: implementing various optimization algorithms.
- PIL, PIL.Image, matplotlib.pyplot: loading and displaying the images.
- torchvision.transforms: treats PIL images and transforms them into torch tensors.
- torchvision.models: training and loading pre-trained models.
- copy: deep copy the models.

## Loading the neural network
I use a pre-trained VGG network with 19 layers (VGG19).

## The content loss function
The content loss is taking as input the feature maps at a layer in a network and returning the weighted content distance between this image and the content image.

## Reference
[A Neural Algorithm of Artistic Style Paper](https://arxiv.org/pdf/1508.06576.pdf) <br>
[Official Pytorch Neural transfer tutorial](https://pytorch.org/tutorials/advanced/neural_style_tutorial.html#introduction)
