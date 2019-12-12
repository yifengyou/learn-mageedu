<!-- MDTOC maxdepth:6 firsth1:1 numbering:0 flatten:0 bullets:1 updateOnSave:1 -->

- [Dockerfile详解](#dockerfile详解)   
   - [自制docker镜像途径](#自制docker镜像途径)   
   - [关于dockerfile](#关于dockerfile)   
   - [dockefile语法格式](#dockefile语法格式)   
   - [.dockerignore文件](#dockerignore文件)   
   - [docker build](#docker-build)   

<!-- /MDTOC -->
# Dockerfile详解

![20191212_195721_79](image/20191212_195721_79.png)

## 自制docker镜像途径

* 基于容器
  - 二次打包
* 基于dockerfile
  - 从无到有构造

![20191212_195229_30](image/20191212_195229_30.png)

## 关于dockerfile

![20191212_195310_77](image/20191212_195310_77.png)


## dockefile语法格式

* dockerfile = N * [ 注释+指令及其参数 ]
* 指令本身不区分大小写，约定俗成管理，**使用大写**
* 第一条指令必须是**FROM**指令，指定镜像，基于镜像二次构造

![20191212_195436_83](image/20191212_195436_83.png)


## .dockerignore文件

* 文本文件，类似.gitignore，文件排除列表，文件排除名单
* 所有在打包时的文件中，但凡写在.dockerignore文件中的文件不包含，包括.dockerignore本身
* .

## docker build

![20191212_200350_93](image/20191212_200350_93.png)















---
