## Prerequisites
- Linux or macOS (Windows is in experimental support)
- Python 3.6+
- PyTorch 1.3+
- CUDA 9.2+ (If you build PyTorch from source, CUDA 9.0 is also compatible)
- GCC 5+
- [MMCV](https://mmcv.readthedocs.io/en/latest/#installation)

## Installation
I ran experiments with PyTorch 1.8.0, CUDA 11.1, Python 3.7, and Ubuntu 18.04. Other settings that satisfact the requirement would work.

### **If you have a similar environment**
You can simply follow our settings:

Use Anaconda to create a conda environment:

```shell
conda create -n MDE python=3.7
conda activate MDE
```

Install Pytorch:
```shell
conda install pytorch==1.8.0 torchvision==0.9.0 torchaudio==0.8.0 cudatoolkit=11.1 -c pytorch -c conda-forge
```

Then, install MMCV and install the [Monocular-Depth-Estimation-Toolbox](https://github.com/zhyever/Monocular-Depth-Estimation-Toolbox):
```shell
pip install mmcv-full==1.5.0 -f https://download.openmmlab.com/mmcv/dist/cu111/torch1.8.0/index.html

git clone https://github.com/RuijieZhu94/HABins.git
cd HABins
pip install -e .
```

If training, you should install the tensorboard:
```shell
pip install future tensorboard
```


More information about installation can be found in docs of MMSegmentation (see [get_started.md](https://github.com/open-mmlab/mmsegmentation/blob/master/docs/en/get_started.md#installation)).

