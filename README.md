# WideResnet
Wide Residual Networks realized by paddlepaddle

Resnet是近年来广为流行并证明十分有效的backbone网络，随着层数的不断加深，性能会持续提高。然而，随着网络越来越深，性能的提升程度持续下降，因此，训练非常深的resnet会面临“消失的特征复用”问题，从而使网络的收敛速度变得很慢。为解决此问题，WideResNet(简写为WRN)营运而生，该网络减少了网络的层数，但增加了网络的宽度，使得网络性能超过了当前很深很细的网络（如Resnet）。例如，一个简单的16层WRN，在精度和效率方面就超过了先前所有的深度resnet（包括一千层的深度resnet）。WRN在CIFAR,SVHN,COCO上达到了SOTA指标，在ImageNet上也有重要的性能提升。

参考文献：https://arxiv.org/abs/1605.07146

## Step:
1、下载cifar10数据集，并解压至data目录下；

2、运行train.py
