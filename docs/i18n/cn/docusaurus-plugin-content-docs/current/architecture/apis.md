---
sidebar_position: 4
sidebar_label: "API"
---

# API

## CRD 对象类

HwameiStor 在 Kubernetes 已有的 PV 和 PVC 对象类基础上，HwameiStor 定义了更丰富的对象类，把 PV/PVC 和本地数据盘关联起来。

| Kind              | 缩写       | 功能                  |
|-------------------|----------|---------------------|
| LocalDiskNode     | ldn      | 裸磁盘类型数据卷的存储节点       |
| LocalDisk         | ld       | 节点上数据盘，自动识别空闲可用的数据盘 |
| LocalDiskVolume   | ldv      | 裸磁盘类型数据卷            |
| LocalDiskClaim    | ldc      | 筛选并分配本地数据盘          |
| LocalStorageNode  | lsn      | LVM 类型数据卷的存储节点      |
| LocalVolume       | lv       | LVM 类型数据卷           |
| LocalVolumeExpand | lvexpand | 扩容LVM类型数据卷的容量       |
