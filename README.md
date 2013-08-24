[M9](http://www.meizu.com)
=================

M9 repo is Linux kernel source code for Meizu M9 smartphones. With this repo, you can customize the source code and compile a Linux kernel image yourself. Enjoy it!

HOW TO COMPILE
-----------

###1. Download source code###

  <code>git clone https://github.com/meizuosc/m9.git</code>

###2. Compiling###

  <code>make meizu_defconfig</code>
  
  <code>make -j8 ARCH=arm CROSS_COMPILE=arm-linux-gnueabi-</code>

  Note:
  + Make sure you have arm cross tool chain, maybe you can download [here](http://www.linaro.org/downloads)
  + If you get a poor cpu in your compiling host, you should use "-j4" or lower instead of "-j8"

Get Help
--------

Checkout our community http://bbs.meizu.cn (in Chinese)
