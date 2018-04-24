# Install-TensorFlow-on-Jetson-TX2-with-JetPack-3.1


###First: Install Jetpack 3.1 from https://developer.nvidia.com/embedded/dlc/jetpack-l4t-3_1 and if you don't have an account on Nvidia, make an account and download it.
<br>

You will require 1 PC with Ubuntu 14.04 for flashing jetpack to your Jetson TX2.


#Second: Install Tensor Flow from wheel file:

###For Python 2.7 Users: 

* sudo apt-get install -y python-pip python-dev

* sudo pip install tensorflow-wheel-file


###For Python 3.5 Users:

* sudo apt-get install -y python3-pip python3-dev

* sudo pip3 install tensorflow-wheel-file

#Third: Install Keras:

* sudo pip3 install keras

#Forth: Install all other required packages used for coding

###1. Install h5py package:

* sudo apt-get install python3-h5p

###2.  install matplotlib lib:

* sudo apt-get build-dep python3-matplotlib

* sudo apt-get install python3-matplotlib 

###3. Install Jupyter Notebook:

* sudo pip3 install jupyter

###4. Install Spicy

* sudo apt install python3-numpy python3-scipy

###5. To turn ON all CPU’s:

sudo nvpmodel -m 0

###6. To speed up:

* sudo ./jetson_clocks.sh

