# GraphGP
An official implementation for "[Graph-Structured Gaussian Processes for Transferable Graph Learning](https://openreview.net/pdf?id=eZbqD9BoXe)" (NeurIPS'23).

## Environment Requirements
The code has been tested under Python 3.10. The required packages are as follows:
* torch>=1.13.0+cu117
* numpy>=1.24.3
* gpytorch>=1.10
* torch_geometric>=2.3.0
* setuptools>=57.0.0

## Data Sets
The raw Twitch data sets (associated with the number of views) can be found at [MUSAE](https://github.com/benedekrozemberczki/MUSAE). Other data sets can directly be downloaded from [torch_geometric.datasets](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html) API.

## Acknowledgement
This is the latest source code of **GraphGP** in NeurIPS'23. If you find that it is helpful for your research, please consider to cite our paper:

```
@inproceedings{wu2023graph,
  title={Graph-Structured Gaussian Processes for Transferable Graph Learning},
  author={Wu, Jun and Ainsworth, Elizabeth and Leakey, Andrew and Wang, Haixun and He, Jingrui},
  booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
  year={2023},
}
```

## Reference
This project is built based on [GPyTorch](https://github.com/cornellius-gp/gpytorch) and [PyG](https://github.com/pyg-team/pytorch_geometric).
