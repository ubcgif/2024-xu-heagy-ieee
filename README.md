# A Test-Time Learning Approach to Reparameterize the Geophysical Inverse Problem With a Convolutional Neural Network

_Anran Xu and Lindsey Heagy_

https://doi.org/10.1109/TGRS.2024.3424659

![thumbnail](./paper/thumbnail.png)

## Summary

Regularization is critical for solving ill-posed geophysical inverse problems. Explicit regularization is often used, but there are opportunities to explore the implicit regularization effects that are inherent in a neural network structure. Researchers have discovered that the convolutional neural network (CNN) architecture inherently enforces a regularization that is advantageous for addressing diverse inverse problems in computer vision (CV), including denoising and in-painting. In this study, we examine the applicability of this implicit regularization to geophysical inversions. The CNN maps an arbitrary vector to the model space. The predicted subsurface model is then fed into a forward numerical simulation to generate corresponding predicted measurements. Subsequently, the objective function value is computed by comparing these predicted measurements with the observed measurements. The backpropagation algorithm is employed to update the trainable parameters of the CNN during the inversion. Note that the CNN in our proposed method does not require training before the inversion; rather, the CNN weights are estimated in the inversion process; hence, this is a test-time learning (TTL) approach. In this study, we choose to focus on the direct current (dc) resistivity inverse problem, which is representative of typical Tikhonov-style geophysical inversions (e.g., gravity and electromagnetic), to test our hypothesis. The experimental results demonstrate that the implicit regularization can be useful in some dc resistivity inversions. We also provide a discussion of the potential sources of this implicit regularization introduced from the CNN architecture and discuss some practical guides for applying the proposed method to other geophysical methods.

## Citation

A. Xu and L. J. Heagy, "A Test-Time Learning Approach to Reparameterize the Geophysical Inverse Problem With a Convolutional Neural Network," in IEEE Transactions on Geoscience and Remote Sensing, vol. 62, pp. 1-12, 2024, Art no. 5919912, doi: 10.1109/TGRS.2024.3424659.

```

@article{xu_inverse_2024,
author={Xu, Anran and Heagy, Lindsey J.},
journal={IEEE Transactions on Geoscience and Remote Sensing}, 
title={A Test-Time Learning Approach to Reparameterize the Geophysical Inverse Problem With a Convolutional Neural Network}, 
year={2024},
volume={62},
number={},
pages={1-12},
doi={10.1109/TGRS.2024.3424659}}

```
