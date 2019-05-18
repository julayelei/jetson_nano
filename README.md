# jetson_nano

(This is still a work in progress.  I plan to add more scripts into this repository and write some more blog posts about them.) 

This repository holds the scripts/programs I use to set up the software development environment on my Jetson Nano.

To set Jetson Nano to 10W performance mode ([reference](https://devtalk.nvidia.com/default/topic/1050377/jetson-nano/deep-learning-inference-benchmarking-instructions/)), execute the following from a terminal:

   ```shell
   $ sudo nvpmodel -m 0
   $ sudo jetson_clocks
   ```

Here is a list of blog posts realted to the scipts in this repository:

* [Setting up Jetson Nano: The Basics](https://jkjung-avt.github.io/setting-up-nano/)
* [Installing OpenCV 3.4.6 on Jetson Nano](https://jkjung-avt.github.io/opencv-on-nano/)
* [Installing and Testing SSD Caffe on Jetson Nano](https://jkjung-avt.github.io/ssd-caffe-on-nano/)
