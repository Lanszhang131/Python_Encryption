# Python 文件加密脚本0.1

能将Python项目中的py文件进行混淆处理（所有的变量和函数进行替换，并且删除注释、空行等，降低可读性），并且编译为.pyc二进制文件，从而达到保护python源代码的目的。



## 依赖

* python3
* pyminifier



## 用法

1. 使用命令行并且cd到此脚本的文件夹下

2. ```bash
    python encrypt.py -d 需要加密的项目文件夹路径 -nd 加密后的项目文件夹路径（选填，默认值为当前脚本文件夹下)
    ```



## 注意事项

1. 路径中不要有中文或者空格



## Todo

1. 使用C++编写加密和解密程序，使用非对称加密对脚本进行加密，进一步提升安全性。



