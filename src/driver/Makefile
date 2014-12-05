obj-m := secbulk.o
secbulk-m := secbulk.o

default:
	make -C /lib/modules/`uname -r`/build M=`pwd` modules

clean:
	make -C /lib/modules/`uname -r`/build M=`pwd` modules clean
