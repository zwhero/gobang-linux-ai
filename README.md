# gobang-linux-ai
基于linux的ai可联机五子棋 

首先将rest_rpc\include中文件和rest_rpc\third\msgpack\include中的文件放入/usr/include 中

然后安装boost库

最后在linux下使用g++ main.cpp -o  gobangc -lboost_system -pthread 编译运行即可

（zouwei，linux大作业）