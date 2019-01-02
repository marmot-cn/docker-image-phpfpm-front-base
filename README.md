# 后端基础服务镜像

---

## 基本编译配置项

* `--enable-zip`
* `--with-tidy`

## 扩展安装

### apt包

#### tidy

* `ibtidy-dev`

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
* `mongodb-1.4.0`
* `gd`
* `iconv`: iconv函数库能够完成各种字符集间的转换
* `mcrypt`: 常用加密算法的封装

## 版本记录

* `1.0`: 初始化基础镜像
* `1.1`: 添加`scws`扩展
* `1.2`: 添加`tidy`扩展
* `1.3`: 升级`mongodb-1.2.10`为`mongodb-1.4.0`