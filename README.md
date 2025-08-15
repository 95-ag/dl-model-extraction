# Model Extraction Attacks

[`door.py`](./door.py) contains the main experiment code. The final project report is available [here](./DL_Project_Group_42_v1.1.pdf).

## About

This project analyzes neural network model extraction techniques. It further investigates whether an extracted model can be used to conduct membership inference attacks and adversarial attacks on the original model.  

## Experimental Setup

- Used victim models for CIFAR-10 (from [zenodo.org](https://zenodo.org/record/4431043)) and custom-trained CIFAR-100 models for extraction attack analysis.
- Varied attacker model architectures to test extraction effectiveness.
- Applied extraction techniques to an out-of-distribution dataset, assembled from downsampled 32x32 ImageNet data. A mapping between ImageNet and CIFAR-10 classes was prepared (note: Deer and Horse classes were sourced online and downsampled).
  
## Resources

- Emulated the victim model using pre-trained models from [zenodo.org/record/4431043](https://zenodo.org/record/4431043).
- Experiments restricted to CIFAR-10 and CIFAR-100 datasets for reproducibility.
- [Project report (PDF)](./DL_Project_Group_42_v1.1.pdf)

## References

- Data-Free Model Extraction: [arxiv.org/abs/2011.14779](https://arxiv.org/pdf/2011.14779.pdf)

## Acknowledgments

- Developed as part of **Deep Learning in Data Science** at KTH Royal Institute of Technology.
- Contributors: Daniel Richards, Adhithyan Kalaivanan, Aishwarya Ganesan
- Forked from original repo: https://github.com/dannyrichy/dl-model-extraction.git
