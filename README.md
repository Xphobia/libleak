# libleak
Libleak- A C library for checking Memory Leak.

# Build from source
1. Get source code
```
  $ git clone --recursive git@github.com:Xphobia/libleak.git
  $ cd libleak
```
2. Install libbacktrace
 ```
  $ cd libbacktrace
  $ ./configure --enable-shared
  $ make
  $ make install
  $ cd ..
  $ echo "/usr/local/lib" > /etc/ld.so.conf.d/libbacktrace.conf
  $ ldconfig
 ```
 3. Compile
 ```
  $ make
 ```

# How to use

Please read README-libleak.md
