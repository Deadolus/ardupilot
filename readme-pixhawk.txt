How to prepare for compiling for pixhawk:

Links:
http://dev.ardupilot.com/wiki/building-the-code-onlinux/
http://pixhawk.org/dev/toolchain_installation_lin

Commands:
. ~/.profile
export PATH=$PATH:/home/eglis/workspace/gcc-arm-px4/gcc-arm-none-eabi-4_7-2014q2/bin/

make px4-clean
make px4-v2
make px4-v2-upload

