### Build Opencv in Ubuntu
```Shell
Follow in link: https://learnopencv.com/install-opencv-4-on-ubuntu-18-04/
```

### Building PCN

Build the library
```Shell
sudo apt-get install -y libgoogle-glog-dev libopencv-dev libboost-system-dev libprotobuf-dev protobuf-compiler libopenblas-dev libcaffe-cpu-dev
```
For python interface (only supported in Ubuntu 18.04):
```Shell
make
sudo make install
```
```Shell
python3 PCN_api.py
```
