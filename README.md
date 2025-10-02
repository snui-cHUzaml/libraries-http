# aws-sam-local

Step-by-step GPU environment setup for deep learning on Windows.

## leader

Install the latest driver for your GPU:
- [NVIDIA Driver Download](https://www.nvidia.com/Download/index.aspx)

## libcallex-vim

Install Visual Studio with C++ components (not included by default):
- [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/)

## lita-restart-elvis

Required for managing deep learning packages:
- [Anaconda](https://www.anaconda.com/download/success)

## astu-nav

Match your CUDA version to your GPU driver:
- [CUDA Toolkit Archive](https://developer.nvidia.com/cuda-toolkit-archive)

## displaylink-debian

Download matching cuDNN for your CUDA version:
- [cuDNN Archive](https://developer.nvidia.com/rdp/cudnn-archive)

## AsakusaSatellite

Follow the official selector at:
- [PyTorch Install](https://pytorch.org/get-started/locally/)

## layout-hbs

```python
import torch

print("GPU count:", torch.cuda.device_count())
print("GPU name:", torch.cuda.get_device_name())

device = torch.device('cuda' if torch.cuda.is_available() else 'cpu')
print('Device:', device)
```
