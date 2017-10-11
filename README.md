# VGGVox

This directory contains code to import and evaluate the Speaker Identification and Verification models pretrained on the VoxCeleb dataset as described in the [paper](https://www.robots.ox.ac.uk/~vgg/publications/2017/Nagrani17/nagrani17.pdf): 

``` 
A. Nagrani, J. S. Chung, A. Zisserman, VoxCeleb: a large-scale speaker identification dataset, INTERSPEECH, 2017
``` 

The dataset can be downloaded directly from [here](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/).

### Prerequisites

To use the models first install the MatConvNet framework.  Instructions can 
be found [here](http://www.vlfeat.org/matconvnet/).


### Installing

The easiest way to use the code in this repo is with the `vl_contrib` package 
manager.  To install, follow these steps: 

1. Install and compile matconvnet by following instructions [here](http://www.vlfeat.org/matconvnet/install/). 

2. Run:

```
vl_contrib install VGGVox
vl_contrib setup VGGVox
```
3. You can then run the demo scripts provided to import and test the models. There are two short demo scripts, for both Identification and Verification. These demos demonstrate how to evaluate the models directly on `.wav` audio files:

```
demo_vggvox_identif
demo_vggvox_verif
```

## Citation
If you use this code then please cite:

```bibtex
@InProceedings{Nagrani17,
  author       = "Nagrani, A. and Chung, J.~S. and Zisserman, A.",
  title        = "VoxCeleb: a large-scale speaker identification dataset",
  booktitle    = "INTERSPEECH",
  year         = "2017",
}
```
## References
A. Nagrani, J. S. Chung, A. Zisserman, VoxCeleb: a large-scale speaker identification dataset, INTERSPEECH, 2017
