# Tensorflow2.0ForOldComputers   for Linux
A TensorFlow 2.0 .whl file built with an old processor/computer (for  Linux).

![Old Computer](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/Acer_Aspire_8920_Gemstone.jpg/640px-Acer_Aspire_8920_Gemstone.jpg)


As this file is too big for GitHub I upload it on MediaFire. 

Follow this link :
http://www.mediafire.com/file/w4iduu2ypqefd98/tensorflow-2.0.0-cp36-cp36m-linux_x86_64.whl/file


As you may know,  since TensorFlow 1.6, official binaries use AVX instructions which may not run on older CPUs.
I compiled this 2.0 version under Ubuntu 18.04.3 LTS with a HP Pavillon dv6 notebook running with an Intel Core 2 duo T6600 @2.20GHZ x 2 which is an old CPU (2009) not compatible with AVX instructions nor SSE.

See Technical Specifications for this CPU on Intel WebSite :
https://ark.intel.com/content/www/us/en/ark/products/37255/intel-core-2-duo-processor-t6600-2m-cache-2-20-ghz-800-mhz-fsb.html

(you can check your own CPU on this site)

![Logo Tensorflow](https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/TensorFlowLogo.svg/288px-TensorFlowLogo.svg.png?style=centerme)

Download the file in a directory for example /tmp/tsf :

/>cd tmp

/tmp>mkdir tsf

/tmp>cd tsf 

/tmp/tsf>wget http://www.mediafire.com/file/w4iduu2ypqefd98/tensorflow-2.0.0-cp36-cp36m-linux_x86_64.whl


Then install the .whl file as a standard library in your Python env :

/tmp/tsf>pip install tensorflow-2.0.0-cp36-cp36m-linux_x86_64.whl 


If you want to install this tensorflow in a specific python/Anaconda environment,  please don't forget to activate it before :

(base) /tmp/tsf>conda activate myenv

(myenv) /tmp/tsf>pip install tensorflow-2.0.0-cp36-cp36m-linux_x86_64.whl 

