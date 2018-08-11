# linux-recover-deleted-files
## 尝试用extundelete报错
## 尝试用debugfs报错
怀疑文件系统superblock出现问题，但是如果出现该问题，会导致硬盘无法挂载，所以检查文件系统是否有问题
## fsck检查文件系统，报错
解决方法：安装新版e2fsck

## 惊喜发现debugfs的报错消失

## 尝试extundelete恢复,还是报错
extundelete: Filesystem has unsupported feature(s) when trying to open filesystem /dev/sdb
