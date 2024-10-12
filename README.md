# Python实现阿里云域名DDNS支持ipv4和ipv6

Platform: Windows

需要安装的库：
```
pip install aliyun-python-sdk-core-v3
pip install aliyun-python-sdk-domain
pip install aliyun-python-sdk-alidns
pip install requests
```

因使用网络接口会获取到临时ipv6地址，因此在源仓库的基础上修改获取ipv6的方法。

其他详细使用方法：[https://blog.zeruns.tech/archives/507.html](https://blog.zeruns.tech/archives/507.html)

# 特别注意：

在windows的任务计划程序当中，如果选择的是程序是/xxx/python.exe，那么每次执行任务的时候都会弹出一个窗口，再加上如果是通过网口获取的地址，窗口持续时间会很长，在5分钟一次的重复执行过程中会影响使用，因此最好使用python.exe同等文件夹下的pythonw.exe，此程序执行将不会弹出窗口。
