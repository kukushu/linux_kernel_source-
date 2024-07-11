# wait_queue
等待队列有等待队列头与等待队列元素组成

![](wait_queue_image.png)

![](1_wait_queue_image.png)

创建等待队列项

![](6_wait_queue_image.png)

![](7_wait_queue_image.png)

这是各测试代码，预编译以后为

![](8_wait_queue_image.png)

可以看出等待队列项wait\_queue\_t的private指向了current进程

等待队列头的创建

![](9_wait_queue_image.png)

![](10_wait_queue_image.png)

展开是

![](11_wait_queue_image.png)

向等待头加入等待项

![](12_wait_queue_image.png)

![](13_wait_queue_image.png)

![](14_wait_queue_image.png)

等待事件发生

不可中断阻塞

![](16_wait_queue_image.png)

might\_sleep有可能为空

如果条件成立不需要加入直接break

这里先讲一下do{}while(0)

![](17_wait_queue_image.png)

![](18_wait_queue_image.png)

![](19_wait_queue_image.png)

![](21_wait_queue_image.png)

这里的({})是一个复合语句表达式

![](20_wait_queue_image.png)

为了便于理解精简

![](22_wait_queue_image.png)

![](23_wait_queue_image.png)

![](24_wait_queue_image.png)

![](25_wait_queue_image.png)

![](26_wait_queue_image.png)

首先定义一个等待项，

![](27_wait_queue_image.png)

![](28_wait_queue_image.png)

![](29_wait_queue_image.png)

将等待项加入等待队列

判断条件是否满足，是break,就可以进行该进程

否则这里的cmd为shedule()进入进程调度

接下来看wake\_up

![](30_wait_queue_image.png)

![](31_wait_queue_image.png)

![](32_wait_queue_image.png)

这里的func就是当初初始化等待队列项的

![](33_wait_queue_image.png)

![](34_wait_queue_image.png)

![](35_wait_queue_image.png)

![](36_wait_queue_image.png)

![](37_wait_queue_image.png)

![](39_wait_queue_image.png)

![](38_wait_queue_image.png)

![](41_wait_queue_image.png)