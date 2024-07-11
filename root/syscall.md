# syscall
![](syscall_image.png)

这是用户层系统调用看到的样子

我们来看一个真实的案例

![](1_syscall_image.png)

![](2_syscall_image.png)

![](3_syscall_image.png)

这样最终有了sys\_read

![](4_syscall_image.png)

这里有个系统调用表

![](5_syscall_image.png)

![](6_syscall_image.png)

这样类似\[0\]=sys\_read就产生了。