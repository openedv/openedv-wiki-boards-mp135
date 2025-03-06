---
title: '小节前言'
sidebar_position: 1
---

# 小节前言

&emsp;&emsp;ATK-DLMP135开发板在出厂时已经固化好系统到核心板eMMC储存上了，所以用户可以跳过本章节，无需再烧写系统到开发板，直接上机测试或者使用即可。

&emsp;&emsp;但是由于以下原因用户可能需要重新烧写出厂系统：<br />
&emsp;&emsp;（1）由于出厂系统固件更新，可能优化或者更新了系统；<br />
&emsp;&emsp;（2）由于出厂系统被损坏，修改或者删除了里面的文件，启动不起来，想恢复到出厂系统；<br />
&emsp;&emsp;（3）由于在开发过程，烧写了自己的uboot、内核及系统等，但是无法验证硬件功能，需要烧写回出厂系统，先验证硬件是否正常工作，再修改源码。

&emsp;&emsp;这里我们提供两种方式烧写系统到开发板，如下：<br />
&emsp;&emsp;（1）Windows下使用STM32CubeProgrammer烧写系统，需要使用USB3.0接口，请勿使用USB2.0接口（因为会烧写比较慢！虽然板子OTG是2.0的）；<br />
&emsp;&emsp;（2）Linux下使用STM32CubeProgrammer烧写系统，需要使用USB3.0接口；

