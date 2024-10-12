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
