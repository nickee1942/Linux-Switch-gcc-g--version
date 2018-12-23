# Linux-Switch-gcc-g++-version
* Install the version you want to use
$sudo apt-get install gcc-x.x
* Add this version into the list, make a priority, following example make the priority 100
$sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-x.x 100 
$sudo update-alternatives --config gcc
* If it already had more than one version in the list, then it will notify you the version, and you chould switch version between them
* Use the above step to switch g++ version
