# opencv
opencv build notes


## instructions

```shell
sudo yum groupinstall "Development Tools"
 sudo yum install cmake
 sudo yum install ant

git clone https://github.com/Itseez/opencv.git && cd opencv

git checkout 2.4.6.2

mkdir release && cd release

cmake -DBUILD_SHARED_LIBS=ON -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/ ..
 make
 sudo make install
```
