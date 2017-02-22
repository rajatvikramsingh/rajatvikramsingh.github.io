---
title: Transfer Learning a VGG-16 for CIFAR-10 Dataset
layout: default
members: Rajat Vikram Singh
description: Deep Learning Individual Project
category: project
---

Trained a CNN to classify the cifar-10 database by using a vgg16 trained on Imagenet as base. The approach is to transfer learn using the first three blocks (top layers) of vgg16 network and adding FC layers on top of them and train it on CIFAR-10. Trained using two approaches for 50 epochs: 1. Keeping the base model's layer fixed, and 2. By training end-to-end. First approach reached a validation accuracy of 95.06%. Second approach reached a validation accuracy of 97.41%. [[Github]](https://github.com/rajatvikramsingh/cifar10-vgg16) [[CNN Architectures - Review]]({{ site.url }}/media/DeepLearning_ImageNetWinners.pdf) [[Adversarial Examples - Review]]({{ site.url }}/media/DeepLearning_AdversarialExamples.pdf)
