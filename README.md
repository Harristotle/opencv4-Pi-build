# opencv4-Pi-build
This is a place for a tarball of the opencv and opencv_contrib version 4.0.0 built on the raspberry pi

OpenCV takes forever to build on the pi, and some of my collaborators just want a binary to quickly get started.

Download the tarball into /home/pi

tar -xzf opencv.tgz
cd opencv/build
sudo make install

