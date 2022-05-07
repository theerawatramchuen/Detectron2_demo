# Detectron2_demo
### Installation & Demo on OD, IS, KP inferencing Youtube
https://www.youtube.com/watch?v=Pb3opEFP94U
#### Detectron2 Installation
#### Fixed "AssertionError: Torch not compiled with CUDA enabled" as below pytorch verion to 
#### enable cuda device as below test cl
#### >>> import torch
#### >>> torch.cuda.is_available()
#### True
$ pip3 install torch==1.10.1+cu113 torchvision==0.11.2+cu113 torchaudio===0.10.1+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html
