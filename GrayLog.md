=================================
Giới thiệu
=================================
Graylog (formerly known as Graylog2) is an open source log management platform, helps you to collect, index and analyze any machine logs on a centralized location. This guide helps you to install Graylog2 on Ubuntu 14.04, also focus on installation of four other components that makes Graylog2 a power full log management tool.

=================================
Giới thiệu các thành phần
=================================

1. MongoDB – Stores the configurations and meta information.

2. Elasticsearch – Stores the log messages and offers a searching facility, nodes should have high memory as all the I/O operations are happens here.

3. GrayLog – Log parser, it collect the logs from various inputs.

4. GrayLog Web interface = provides you the web-based portal for managing the logs.


Yêu cầu cài đặt môi trường
**************************
    
    ``$ java -version``
    
    ``java version "1.8.0_60"``
    
    ``Java(TM) SE Runtime Environment (build 1.8.0_60-b27)``
    
    ``Java HotSpot(TM) 64-Bit Server VM (build 25.60-b23, mixed mode)``



Các bước cài đặt
****************
