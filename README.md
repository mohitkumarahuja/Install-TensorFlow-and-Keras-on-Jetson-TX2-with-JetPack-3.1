# Install-TensorFlow-on-Jetson-TX2-with-JetPack-3.1


1. Install h5py package:

sudo apt-get install python3-h5p

2.  install matplotlib lib:

sudo apt-get build-dep python3-matplotlib

sudo apt-get install python3-matplotlib 

3. Install Cuda on jetson:

Install jetpack compatible with github repository.

4. Install tensor flow:

Install pip and then install wheel file from here : https://github.com/jetsonhacks/installTensorFlowJetsonTX

5. Install Jupyter Notebook:

sudo pip3 install jupyter

6. Install Spicy

sudo apt install python3-numpy python3-scipy

7. To turn ON all CPU’s:

sudo nvpmodel -m 0

8. To speed up:

sudo ./jetson_clocks.sh

