# 后端基础服务镜像

---

## 基本编译配置项

* `--enable-zip`

## 扩展安装

### apt包

#### memcached

* `libmemcached-dev`
* `zlib1g-dev`

#### mongo

* `libssl-dev`

#### gd

* `libfreetype6-dev`
* `libjpeg62-turbo-dev`
* `libmcrypt-dev`
* `libpng12-dev`

### ext

* `memcached-3.0.3`
* `mongo-1.2.10`
* `gd`
* `iconv`: iconv函数库能够完成各种字符集间的转换
* `mcrypt`: 常用加密算法的封装

## 版本记录

* `0.1`: 初始化基础镜像