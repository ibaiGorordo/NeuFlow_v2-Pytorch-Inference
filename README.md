# NeuFlow v2 Pytorch Inference

![NeuFlow_v2 Pytorch Inference](https://github.com/user-attachments/assets/309ade03-c1af-4539-81c0-c7cae8d0222e)

<a href='https://arxiv.org/abs/2409.02095'><img src='https://img.shields.io/badge/arXiv-2408.10161-b31b1b.svg'></a> &nbsp;

Simplified repository for Pytorch inference based on the Official PyTorch implementation: https://github.com/neufieldrobotics/NeuFlow_v2

## Installation 

``` bash
git clone https://github.com/ibaiGorordo/NeuFlow_v2-Pytorch-Inference.git
cd NeuFlow_v2-Pytorch-Inference
pip install -r requirements.txt
```

## Inference

Inference downloads the pre-trained models from the original repository automatically:
```bash
python example_inference.py
```

## ONNX Export
```bash
python export_onnx.py
```

## License
This original model is licensed under Apache 2.0: https://github.com/neufieldrobotics/NeuFlow_v2/blob/master/LICENSE

## References
- NeuFlow v2: https://github.com/neufieldrobotics/NeuFlow_v2
- Paper: https://arxiv.org/abs/2409.02095
