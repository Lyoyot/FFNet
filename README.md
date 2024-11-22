# FFNet
## Requirements
1. Python 3.6.9 <br>
2. PyTorch 1.3 <br>
3. OpenCV 4.0.1 <br>
4. tensorboardX 2.2 <br>
5. matplotlib <br>
## Dataset
1. Download the dataset from [changedetection.net](https://changedetection.net) and unzip the contents in ./dataset/currentFr <br>
2. Download the dataset_fpm from https://www.alipan.com/t/YMo8sszFArrVJG5Fl1Ct and put the contens in ./dataset/currentFrFPM <br>
3. In the end, ./dataset folder should have the following subfolders: currentFr, currentFrFpm
## Training and Testing
You can run train.py: <br>
'python train.py --empty_bg='no' --recent_bg=0 --num_epochs=30 --set_number=1' <br>
ps. The testing code is at the end of train.py 
## Acknowledgement
This implementation largely depends on [BSUV-Net 2.0](https://github.com/ozantezcan/BSUV-Net). We thank the authors for the contribution.
