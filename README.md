# Detectron2_demo
### Installation & Demo on OD, IS, KP inferencing Youtube
https://www.youtube.com/watch?v=Pb3opEFP94U <br/>
conda install pytorch torchvision torchaudio cudatoolkit=11.0 -c pytorch <br/>
conda install cython <br/>
git clone https://github.com/facebookresearch/detectron2.git <br/>
cd detectron2 <br/>
pip install -e . <br/>
pip install opencv-python <br/>
#### Installation notes: <br/>
Fixed "AssertionError: Torch not compiled with CUDA enabled" as below pytorch verion to enable cuda device as below test python command line <br/>
/>>>import torch<br/>
/>>>torch.cuda.is_available()<br/>
True<br/>
"$ pip3 install torch==1.10.1+cu113 torchvision==0.11.2+cu113 torchaudio===0.10.1+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html"<br/>

