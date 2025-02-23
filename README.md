# LLM-From-Scratch
https://www.youtube.com/watch?v=UU1WVnMk4E8&amp;t=1548s

## Install Libraries
 1. Added Virtual-Env named cuda 
 ```
 python -m venv cuda
 ```
 2. Activated the V-Env
 ```
 source ./cuda/bin/activate
 ```
 3. Install deps
 ```
 pip3 install matplotlib numpy ipykernel jupyter 
 ```
 *Ignored **pylzma** as it is now supported by python OOTB*

4. Install PyTorch 
```
pip3 install torch
```
*CUDA is not available on Macs. Instead, GPU-accelerated PyTorch training is now supported on Mac. See - 
https://pytorch.org/blog/introducing-accelerated-pytorch-training-on-mac/
https://stackoverflow.com/questions/63423463/using-pytorch-cuda-on-macbook-pro*
 


---
___