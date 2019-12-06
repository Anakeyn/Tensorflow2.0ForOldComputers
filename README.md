# Tensorflow2.0ForOldComputers   for Linux
A TensorFlow 2.0 .whl file compiled with an old processor/computer (for  Linux)
As this file is too big for GitHub I upload it on MediaFire. 
Follow this link :
http://www.mediafire.com/file/w4iduu2ypqefd98/tensorflow-2.0.0-cp36-cp36m-linux_x86_64.whl/file#

As you may know,  since TensorFlow 1.6, official binaries use AVX instructions which may not run on older CPUs.
I compiled this 2.0 version under Ubuntu 18.04.3 LTS with a HP Pavillon dv6 notebook with a Intel Core 2 duo T6600 @2.20GHZ x 2 wich is an old CPU (2009) not compatible with AVX instructions nor SSE.
See Technical Specifications for this CPU on Intel WebSite :
https://ark.intel.com/content/www/us/en/ark/products/37255/intel-core-2-duo-processor-t6600-2m-cache-2-20-ghz-800-mhz-fsb.html

Download the file in a directory for example /tmp/tsf  
/>cd tmp
/tmp>mkdir tsf
/tmp>cd tsf 
/tmp/tsf>wget http://www.mediafire.com/file/w4iduu2ypqefd98/tensorflow-2.0.0-cp36-cp36m-linux_x86_64.whl
Then install the .whl file as a standard library in your python env
/tmp/tsf>pip install tensorflow-2.0.0-cp36-cp36m-linux_x86_64.whl 
If you want to install this tensorflow in a specific python/Anaconda environment,  please don't forget to activate it :
(base) /tmp/tsf>conda activate my env
(myenv) /tmp/tsf>

