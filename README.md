# PointAlign: Feature-Level Alignment Regularization for 3D Vision-Language Models

## Installation

Please follow the installation instructions from [MiniGPT-3D](https://github.com/TangYuan96/MiniGPT-3D).

## Data Preparation

Please follow the data preparation instructions from [MiniGPT-3D](https://github.com/TangYuan96/MiniGPT-3D).

## Training

```bash
torchrun --nproc_per_node 4 train.py --cfg-path ./train_configs/MiniGPT_3D/stage_2.yaml
```

## Evaluation

Please follow the evaluation instructions from [MiniGPT-3D](https://github.com/TangYuan96/MiniGPT-3D).

## Acknowledgement

This work builds upon [MiniGPT-3D](https://github.com/TangYuan96/MiniGPT-3D). We thank the authors for their excellent codebase.
