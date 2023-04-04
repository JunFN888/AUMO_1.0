.. image:: images/images_0/8.png

================
航空插座接口定义
================

 **采用 M8 6pin 的航空插座（公座），用于 GPS 通信和外部触发输入。**

.. csv-table:: 
  :header: "PIN脚", "信号名","方向","说明"
  :widths: 10, 30, 10, 30


  " 1 ",FPGA_TRIG , 输入 ,"外部摄像头同步触发                    "
  " 2 ",GPS_PPS   , 输入 ,"GPS PPS 同步输入"
  " 3 ",GPS_RXD   , 输入 ,"GPS 串口通信 RXD，TTL 电平"
  " 4 ",GPS_TXD   , 输出 ,"GPS 串口通信 TXD，TTL 电平"
  " 5 ",GND       , ——    ,"参考地"
  " 6 ",GPS       , 电源 ,"输出 默认 3.3V 输出，支持 5V（可选）"

.. image:: images/images_2/4.png

 

*A16 车载摄像头 GMSL 采集卡*    - `AUMO官方网站 <https://www.aumo.cn>`_