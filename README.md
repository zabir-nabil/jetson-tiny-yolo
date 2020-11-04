# jetson-tiny-yolo
Running tiny yolo on jetson nano

### Installation

* An SD card >= 32 GB

* Jetpack 4.4 
  - [Jetpack installation](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write)

* [Prerequisite installation](https://jkjung-avt.github.io/jetpack-4.4/)

* [tensorflow installation](https://docs.nvidia.com/deeplearning/frameworks/install-tf-jetson-platform/index.html)
  - `sudo apt-get update`
  - `sudo apt-get install libhdf5-serial-dev hdf5-tools libhdf5-dev zlib1g-dev zip libjpeg8-dev liblapack-dev libblas-dev gfortran`
  - `sudo apt-get install python3-pip`
  - `sudo pip3 install -U pip testresources setuptools==49.6.0`
  - `sudo pip3 install -U numpy==1.16.1 future==0.18.2 mock==3.0.5 h5py==2.10.0 keras_preprocessing==1.1.1 keras_applications==1.0.8 gast==0.2.2 futures protobuf pybind11`
  - `sudo pip3 install --pre --extra-index-url https://developer.download.nvidia.com/compute/redist/jp/v44 tensorflow`
