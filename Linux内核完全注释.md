Linux内核完全注释 -By 赵炯
基于Linux内核 v0.11，代码总量不超过2万行（如今的内核代码都在几百万行以上） 它不包括虚拟文件系统（VFS），ext2或ext3文件系统，网络子系统，新的复杂的内存管理机制。

预备技能及需要参考的资料：
1.会一些80x86编程知识  《Intel 80x86 Rrogrammer's Reference Manual》
80x86硬件体系结构和接口编程的知识与资料
2. M.J.Bach 的《Unix 操作系统设计》 Andrew S.Tanenbaum 的《操作系统设计与实现》


Linux 0.11版内核使用的文件子系统是MINIX 1.0文件系统，而不是Ext2（最新的是Ext3？）文件系统 

11111
在oldlinux.org网站上下载文件

第1章：
Unix最初的开放原代码版本 GNU计划 POSIX标准 MINIX系统 Internet是Linux诞生的五个支柱。 