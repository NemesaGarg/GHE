# GHE
Compilation step:
gcc -g -c -fPIC -o ghe.o ghe.c
gcc -g -shared -o libdpst.so.1 ghe.o
