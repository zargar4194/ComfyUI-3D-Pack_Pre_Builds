# ComfyUI-3D-Pack_Pre_Builds
wheel of  ComfyUI-3D-Pack python3.10 pytorch=2.3.1 pytorch-cuda=12.1 

**********************************************************************
** Visual Studio 2022 Developer Command Prompt v17.6.5
** Copyright (c) 2022 Microsoft Corporation
**********************************************************************
install cuda 12.1 : https://developer.nvidia.com/cuda-12-1-0-download-archive

C:\Program Files\Microsoft Visual Studio\2022\Community>conda create --name pytorch3d
C:\Program Files\Microsoft Visual Studio\2022\Community>conda activate pytorch3d
(pytorch3d) C:\Program Files\Microsoft Visual Studio\2022\Community>set CUDA_HOME="C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7"
(pytorch3d) C:\Users\dhruvapathak\Projects\A\B>conda install pytorch=2.3.1 torchvision pytorch-cuda=12.1 -c pytorch -c nvidia
(pytorch3d) C:\Users\dhruvapathak\Projects\A\B>conda install -c fvcore -c iopath -c conda-forge fvcore iopath
(pytorch3d) C:\Users\dhruvapathak\Projects\A\B>pip install "git+https://github.com/facebookresearch/pytorch3d.git@stable