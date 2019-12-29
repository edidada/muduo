[csdn 错误：/bin/sh: 1: protoc: not found](https://blog.csdn.net/zhangxiao93/article/details/51768899)


使用muduo源码中的脚本build.sh进行到一半报错:

```shell

sudo apt-get install protobuf-compiler

```

~/build/release

`doxygen : 依赖: libclang1-3.6 (>= 3.2) 但是它将不会被安装`


```shell

cd /home/edidada/build/release-cpp11
export CTEST_OUTPUT_ON_FAILURE=TRUE
echo $CTEST_OUTPUT_ON_FAILURE
cd /home/edidada/muduo
doxygen

```

Cmake组织的代码
https://github.com/chenshuo/muduo-tutorial
moduo支持bazel Cmake make

日志使用的自己写的？


fastcgi写http接口？
