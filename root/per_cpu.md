# per_cpu
[http://www.wowotech.net/kernel\_synchronization/per-cpu.html](http://www.wowotech.net/kernel_synchronization/per-cpu.html)

https://www.dingmos.com/index.php/archives/16/

![](6_per_cpu_image.png)

![](8_per_cpu_image.png)

![](9_per_cpu_image.png)

![](10_per_cpu_image.png)

![](per_cpu_image.png)

![](11_per_cpu_image.png)

![](1_per_cpu_image.png)

![](2_per_cpu_image.png)

![](3_per_cpu_image.png)

![](4_per_cpu_image.png)

![](5_per_cpu_image.png)

![](12_per_cpu_image.png)

![](13_per_cpu_image.png)

具体来看一看副本是如何复制出来的，关键就是这个函数

![](14_per_cpu_image.png)

这个函数在start\_kernel中调用

其中的\_\_per\_cpu\_offset保存了全部cpu的偏移量