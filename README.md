# OpenCV & Caffe: Deep Leaning Examples

Some examples showing how to make real time classification with a Cifar10-trained CNN (With Caffe framework) and a bit of OpenCV, Two IPython notebooks are provided corresponding tho the following two examples:

### Example1

This notebook show how to read random frames from an OpenCV's VideoCapture (that can be a video or a webcam) and perform
the classification process on them. Notice that this example does not train the neural network but loads it form the disk, 
you need a pre-trained network to use this example.

<img src="https://github.com/lopeLH/DeepLearning-CaffeExamples/blob/master/ExamplesWorking/bird.png"  width=500 height=150 />

### Example2

This notebook show how to read sequentian frames from an OpenCV's VideoCapture (that can be a video or a webcam) and perform
the classification process in real time. Notice that this example does not train the neural network but loads it form the disk, 
you need a pre-trained network to use this example.

<img src="https://github.com/lopeLH/DeepLearning-CaffeExamples/blob/master/ExamplesWorking/cat.PNG"  width=350 height=250 />

#### prerequisites:

To use this examples you need to install a lot of things:
- OpenCV an all its dependencies
- Caffe and all its dependencies (http://caffe.berkeleyvision.org/)
- IPython

To make your life easier we are providing a VirtualBox virtual machine with everything you need already installed.
You can find it here:

https://drive.google.com/folderview?id=0B_bFVannGBIhSkJubXptZVpIVU0&usp=sharing

files needed are inside this folder: /home/rna2/Seminario
username: rna2
password: 222222
