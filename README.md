A derivation and update of Bullet-NASM-code by conversion to YASM. The key difference between this program and the NASM one is the function PAUSE has been changed to TIME_OUT; due to compiler error.

Compiles with commands:

yasm barrel.asm -fbin -obarrel.com

on xubuntu 16.04 with nasm installed.

Runs with:

dosbox ./barrel.com -exit
