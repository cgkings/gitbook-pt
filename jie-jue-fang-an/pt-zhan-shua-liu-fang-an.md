# PT站刷流方案

### 硬件

1、大带宽--1G口，2G口，甚至10G口

2、高读取效率--硬盘

2.1 IO性能：有些石头盘、钻石盘读取才10M/s，这种盘就算是10G口，上传速度也跑不起来

2.2 IO负载：这个要实际测一下，iotop是个很好的工具，有些设备测IO是能跑到100M，但是实际运行下载上传任务，才跑到50M/S，IO已经负载99%了，就是所谓的卡IO或IO爆炸，这样你就会发现速度总是上到xxM左右又很快掉下了，无法持续的跑满带宽

3、处理速度--CPU、内存

跟玩游戏一样，木桶效应，大带宽要想稳定跑出来，仍然需要机能足够，CPU 100%不可怕，同样100%，有的设备可以正常刷流，有的设备不仅速度跑不满，还可能卡掉bt客户端，甚至直接掉线也可能

### 软件
