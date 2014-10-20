#简介
完成与ip地址和网段相关的一系列操作

#功能列表
##ipoperate
* IP地址与二进制间转换
* 网段与二进制间转换
* IP地址与整数间转换
* 网段与地址范围的转换
* 网段合并为网段
* 网段的掩码格式和CIDR格式之间转换

##iprange
* 将连续的IP地址合并为范围

#用法
##iprange

    cat list_file | python iprange.py

或者

    python iprange.py list_file
