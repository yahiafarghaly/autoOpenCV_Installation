# autoOpenCV_Installation
it contains a bash shell script for automating the installation of the opencv on ubuntu 14.04

it does all the job required to set the latest opencv (from official repo)  + extra modules(from opencv_contrib repo) on your machine (tested on ubuntu 14.04 and should work on the others).

# what does it do ?
1- Download opencv official repo + opencv_contrib repo in a directory called "opencv_latest"
2- make the installation of opencv using c++/python on your machine.
3- if CUDA exists , it will add the libary support for CUDA in opencv.
4- create a simple alias to be able to compile your opencv code without the need of defining the includes/libs paths.

# run the script as following for the first time.
./setopenCV.sh git

# if you have already the opencv official repo  +  opencv_contrib repo 
(I assume you put this script beside the opencv_latest directory)

./setopenCV opencv_latest/opencv


# TODO
Change the cmake parameters according to your needs.
