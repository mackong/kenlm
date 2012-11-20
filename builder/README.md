Dependencies
============

Misc Libraries
--------------

```bash
sudo apt-get install libboost1.48-dev
sudo apt-get install cmake
```

Getting TPIE
------------

This builder depends on TPIE (Templated Portable I/O Environment).
URL: https://github.com/thomasmoelhave/tpie

Instructions for obtaining, building and installing TPIE:

```bash
wget https://github.com/thomasmoelhave/tpie/archive/v1.0rc2.zip
unzip v1.0rc2.zip
cd tpie-1.0rc2/
cmake .
make -j4
sudo make install
```

Building
========

```bash
bjam
```

Testing
=======

```bash
# See script file for more comments
./test.sh
```