# Detectron2_demo
### Installation & Demo on OD, IS, KP inferencing Youtube
https://www.youtube.com/watch?v=Pb3opEFP94U <br/>
git clone 
conda create -n detectron2 python=3.8
conda activate detectron2
conda install pytorch torchvision torchaudio cudatoolkit=11.0 -c pytorch <br/>
conda install cython <br/>
git clone https://github.com/facebookresearch/detectron2.git <br/>
cd detectron2 <br/>
pip install -e . <br/>
pip install opencv-python <br/>
### Installation notes: <br/>
#### How to fix "AssertionError: Torch not compiled with CUDA enabled" as below pytorch verion to enable cuda device as below test python command line <br/>
/>>>import torch<br/>
/>>>torch.cuda.is_available()<br/>
False<br/><br/>
"$ pip3 install torch==1.10.1+cu113 torchvision==0.11.2+cu113 torchaudio===0.10.1+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html"<br/><br/>
/>>>import torch<br/>
/>>>torch.cuda.is_available()<br/>
True<br/><br/>

#### How to fix "ImportError: DLL load failed" while importing win32api on Anaconda Windows<br/>
conda install pywin32


