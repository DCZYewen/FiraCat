# FiraCat
A distributed Object Storage System written in Python .

# Why develop this
现有的随手可用的OSS大多是公有云，类似AWS S3和阿里云OSS，他们拥有强大的功能和复杂的API。私有的OSS系统大多兼容S3 API且难以配置，（比如OpenStack Swift）。但是在最普通的工程中，工程师们可能只需要非常有限的OSS功能，毕竟，在大多数情况下，存储服务是以存储和发放为主。

这时候我们萌生了一个想法，为什么不做一个实用至上的对象存储工具呢？这个工具拥有一般的OSS功能，无敌易用好记的API，RESTful，简化的结构架构。图一个方便部署，方便实用，方便理解，简便逻辑，可变规模。

## Simple First

# Archtecture

See `arch/` 。