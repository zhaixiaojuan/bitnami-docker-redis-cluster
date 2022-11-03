6.2/debian-10/tar-gz/gosu-1.12.0-2-linux-loong64-debian-10.tar.gz 
6.2/debian-10/tar-gz/redis-6.2.1-0-linux-loong64-debian-10.tar.gz
这两个tar包的制作过程：
（1）先从官网拉取x86的包
curl --remote-name --silent https://downloads.bitnami.com/files/stacksmith/gosu-1.12.0-2-linux-amd64-debian-10.tar.gz
curl --remote-name --silent https://downloads.bitnami.com/files/stacksmith/redis-6.2.1-0-linux-amd64-debian-10.tar.gz
解压这两个包，将包中的二进制替换为LA架构的二进制
（2）gosu二进制的制作
见：git@github.com:zhaixiaojuan/gosu.git
（3）redis二进制的制作
见：git@github.com:zhaixiaojuan/redis.git
