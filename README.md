# pod常用操作
**环境说明：**

 
| 主机名 | 操作系统版本 | ip | docker version | kubelet version | 备注 |
| :------: | :------:  | :------: | :------: | :------: | :------: |
| master | Centos 7.6.1810 | 172.27.9.131 |Docker 18.09.6 | V1.14.2 | master主机 |
| node01 | Centos 7.6.1810 | 172.27.9.135 |Docker 18.09.6 | V1.14.2 | node节点 |
| node02 | Centos 7.6.1810 | 172.27.9.136 |Docker 18.09.6 | V1.14.2 | node节点 |


<br>
 &emsp;  &emsp; Pod是kubernetes中你可以创建和部署的最小也是最简单位。一个Pod代表着集群中运行的一个进程。Pod中封装着应用的容器（有的情况下是好几个容器），存储、独立的网络IP，管理容器如何运行的策略选项。Pod代表着部署的一个单位：kubernetes中应用的一个实例，可能由一个或者多个容器组合在一起共享资源

**文章目录：**
# 一、 pod简介
## 1. pod概览
## 2. pod网络
# 二、创建pod的两种方式
## 1. 命令方式
## 2. 文件方式
# 三、标签
## 1. pod使用标签
## 2. 通过标签指定pod创建的节点
# 四、命名空间
## 1. 查看命名空间
## 2. 查看指定命名空间的pod
## 3. 创建命名空间
## 4. pod指定命名空间 
# 五、扩容/缩容
# 六、failover
## 1. pod节点分布查看
## 2. failover测试
# 七、升级及回滚
## 1. 创建deployment
## 2. 升级
## 3. 回滚
# 八、内外网访问
## 1. 创建pod
## 2. 内网访问
## 3. 外网访问
# 九、日志查看
## 1. 查看最近的日志
## 2. 查看前一个容器的日志
## 3. 通过标签查看日志
# 十、删除pod
## 1. 通过删除deployment删除pod
## 2. 通过删除namespace删除pod

<br>
<br>

**详细搭建过程及测试：**


https://blog.51cto.com/3241766/2394283
