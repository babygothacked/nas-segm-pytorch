# Neural Architecture Search of Semantic Segmentation Models (in PyTorch)

This repository provides official models from the paper `Fast Neural Architecture Search of Compact Semantic Segmentation Models via Auxiliary Cells`, available [here](https://arxiv.org/abs/1810.10804)

```
Fast Neural Architecture Search of Compact Semantic Segmentation Models via Auxiliary Cells
Vladimir Nekrasov, Hao Chen, Chunhua Shen, Ian Reid
To appear in CVPR, 2019
```

## Getting Started

For flawless reproduction of our results, the Ubuntu OS is recommended. The models have been tested using Python 3.6.

### Dependencies

```
pip3
Cython
cv2
jupyter-notebook
matplotlib
numpy
Pillow
torch>=1.0
torchvision
```

## Inference Examples

For the ease of reproduction, we have embedded all our examples inside Jupyter notebooks.

### Segmentation

Please refer to results on [PASCAL VOC](./examples/inference/VOC-segm.ipynb)

### Depth Estimation

Please refer to results on [NYUD-v2](./examples/inference/NYU-depth.ipynb)

## License

This project is free to use for non-commercial purposes - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* University of Adelaide and Australian Centre for Robotic Vision (ACRV) for making this project happen
* HPC Phoenix cluster at the University of Adelaide for making the training of the models possible
* PyTorch developers
* Yerba mate tea
