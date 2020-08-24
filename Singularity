Bootstrap:docker
From:centos:7

%labels
MAINTAINER raffenet

%environment

%runscript
echo "This gets run when you run the image!"
hostname

%post
echo "This section happens once after bootstrap to build the image."
yum install mpich
