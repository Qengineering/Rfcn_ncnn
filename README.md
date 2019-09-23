# Rfcn for the ncnn framework
Papers <br/>
https://arxiv.org/pdf/1605.06409.pdf <br/>
Training set: VOC2007+VOC2012 <br/>
Size: 224x224 <br/>
Prediction time: 2484 mSec (RPi 4) <br/>
<br/>
Special made for a bare Raspberry Pi see: https://qengineering.eu/opencv-c-examples-on-raspberry-pi.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/Rfcn_ncnn/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
Traffic.jpg <br/>
rfcn.bin (download this file from: https://drive.google.com/open?id=1_MO5ipSymIxlBAF2elD3AOJyboIdiKEa )<br/>
rfcn.param <br/>
Rfcn.cpb <br/>
rfcn.cpp <br/>
 <br/>
Run Rfcn.cpb with Code::Blocks. Remember, you also need a working OpenCV 4 on your Raspberry. <br/>

![output image]( https://qengineering.eu/images/Rfcn_trafic.jpg )

