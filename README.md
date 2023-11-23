# alist-sync

Alist 多驱动同步工具

利用GitHub Actions实现使用Github的计算资源和网络资源帮忙我们同步各个网盘之间的数据。


## 初步目标，单向有无同步

源盘 -> 多目标盘，若目标盘中有同名文件，跳过同步。

## 二级目标，双向有无同步

便利全部盘，并将别的盘没有的文件同步过去

## 三级目标，按文件的更新时间实现增量同步