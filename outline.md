## 主要内容

这次分享主要分为两大块，分别是git与docker。

## git版本控制

1. 版本控制的基本概念与演变
> 为什么要版本控制
> RCS本地版本控制及其缺陷
> SVN集中式的版本控制的优势和缺陷
> Git分布式的版本控制的诞生

2. git的核心思想与管理逻辑
> 分布式的优点与多个中心的优势
> 操作完全在本地执行
> 记录快照与只添加数据

3. 基本操作
> 文件的三种状态
> 状态切换之间的操作
> 分支与标签

4. gitlab工作流
> 我们采取gitlab的原因
> 一般开发人员的工作流
> 管理人员的工作流

## docker容器使用

1. 容器与虚拟化
> 虚拟化技术的发展
> 与虚拟机对比的优势

2. 基本概念
> Image
> Container
> Volume
> Registry,Swarm,Machine,Compose

3. 基本操作
> docker pull与docker push
> docker run与 -p, -v, -t, -i, -d 
> docker stop, docker start, docker restart
> nsenter, docker attach, docker exec

## jenkins自动化测试（演示）

1. 持续集成与自动化测试
> CI, QA, CD
> jenkins与pipeline
> 使用docker进行自动化测试