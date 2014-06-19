PyCUDA
======

Installation of PyCUDA
-----------------------

1. Check for version of Python.

```bash
Python 3.4.0 (v3.4.0:04f714765c13, Mar 16 2014, 19:25:23) [MSC v.1600 64 bit (AM
D64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

```shell
$ git clone https://github.com/urutu/pycuda.git
$ cd pycuda
$ python configure.py \
    --cuda-root=/where/ever/you/installed/cuda
$ sudo make install
```
This installs PyCUDA for Python 3.

Note for Linux Users
--------------

Installing using Python 2
```shell
$ git clone https://github.com/urutu/pycuda.git
$ cd pycuda
$ python configure.py \
    --cuda-root=/where/ever/you/installed/cuda
$ sudo make install
```

Installing using Python 3
```shell
$ git clone https://github.com/urutu/pycuda.git
$ cd pycuda
$ python3 configure.py \
    --cuda-root=/where/ever/you/installed/cuda
$ sudo make install
```
