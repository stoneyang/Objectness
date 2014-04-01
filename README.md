Objectness
==========
BING Objectness proposal estimator linux/mac/windows version implementation, 
runs at 1000 FPS.
Objectness Proposal estimator运行代码，已经在linux/mac/windows下测试成功，
执行速度超过1000帧每秒。


This is the 1000 FPS BING objectness linux version library for efficient 
objectness proposal estimator following the CVPR 2014 paper BING, please 
consider to cite and refer to this paper.

@inproceedings{BingObj2014,
  title={{BING}: Binarized Normed Gradients for Objectness Estimation at 300fps},
  author={Ming-Ming Cheng and Ziming Zhang and Wen-Yan Lin and Philip H. S. Torr},
  booktitle={IEEE CVPR},
  year={2014},
}

The original author Ming-Ming Cheng has already released the source code for 
windows 64-bit platform. In this library, we intend to release the code for the 
linux/mac/windows users. You can maintain the code with Qt Creator IDE.

Please find the original windows code / FAQ / Paper from this link:
http://mmcheng.net/bing/

In order to make the code running as the original version in windows, you need
to download the images/annotations PASCAL VOC 2007 data from the website.
(http://pascallin.ecs.soton.ac.uk/challenges/VOC/voc2007/#testdata)

We have tested the code, it produces the same accuracy results as the original windows
version, while it runs at 1111 FPS(frame per second) at Ubuntu 12.04 with a Dell T7600 
workstation computer, which has two Intel Xeon E5-2687W (3.1GHz, 1600MHz) and 64 GB 
1600MHz DDR3 Memory.


Author: Ming-ming Cheng removethisifyouarehuman-cmm.thu@gmail.com
Linux Author: Shuai Zheng (Kyle) removethisifyouarehuman-szhengcvpr@gmail.com
Please find more information from http://kylzheng.org/objectness/
Date: 19, February 
