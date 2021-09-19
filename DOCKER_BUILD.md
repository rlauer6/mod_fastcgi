# Building mod_fastcgi.so using a Docker Container

To build `mod_fastcgi.so` using a Docker container, try:

```
make -f Makefile.docker
```

This will download and build Apache and `mod_fastcgi.so`.  If you want
to build a specific version of Apache try:

```
make -f Makefile.docker APACHE_VERSION=2.4.49
```
