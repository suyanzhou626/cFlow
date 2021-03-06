# README #

**The repository is being updated.**

This is official Pytorch implementation of 
"[Uncertainty quantification in medical
image segmentation with Normalizing Flows](https://arxiv.org/abs/2006.02683)", Raghavendra Selvan et al. 2020

![lotenet](models/cflow.png)
### What is this repository for? ###

* Train the proposed model on LIDC and Retina datasets
* Reproduce the reported numbers in the paper
* v1.0

### How do I get set up? ###

* Basic Pytorch dependency
* Tested on Pytorch 1.3, Python 3.6 
* Download preprocessed datasets [from here]()

### Usage guidelines ###

* Kindly cite our publication if you use any part of the code
```
@article{raghav2020cFlowNet,
 	title={Uncertainty quantification in medical image segmentation with Normalizing Flows},
	author={Raghavendra Selvan, Frederik Faye, Jon Middleton, Akshay Pai},
 	journal={arXiv preprint arXiv:2006.02683},
	year={2020}}
```

### Who do I talk to? ###

* raghav@di.ku.dk

### Thanks 
Some parts of our implementation are based on:
* [Prob.U-Net and LIDC data](https://github.com/stefanknegt/Probabilistic-Unet-Pytorch)
* [Planar flows](https://github.com/riannevdberg/sylvester-flows)
* [Glow model](https://github.com/karpathy/pytorch-normalizing-flows)
