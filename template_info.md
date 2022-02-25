# 源码自动生成模板 pandora-boot-archetype-docker

### 概述

* 模板: pandora-boot-archetype-docker
* 模板答疑人: [子观](https://work.alibaba-inc.com/nwpipe/u/64988)
* 模板使用时间: 2021-02-15 20:13:51

### Docker
* Image: reg.docker.alibaba-inc.com/bootstrap/image
* Tag: 0.1
* SHA256: e4b70f4f7d0b60aa3e5666eba441a376b31ec6e0bd550a4efc5af8f057c6d7d8

### 用户输入参数
* repoUrl: "git@gitlab.alibaba-inc.com:tc-logistics-dms/tc-logistics-dms-supplier.git" 
* appName: "tc-logistics-dms-supplier" 
* javaVersion: "1.8" 
* groupId: "com.alibaba.middleware" 
* artifactId: "bootstrap" 
* operator: "91461" 

### 上下文参数
* appName: tc-logistics-dms-supplier
* operator: 91461
* gitUrl: git@gitlab.alibaba-inc.com:tc-logistics-dms/tc-logistics-dms-supplier.git
* branch: master


### 命令行
	sudo docker run --rm -v `pwd`:/workspace -e repoUrl="git@gitlab.alibaba-inc.com:tc-logistics-dms/tc-logistics-dms-supplier.git" -e appName="tc-logistics-dms-supplier" -e javaVersion="1.8" -e groupId="com.alibaba.middleware" -e artifactId="bootstrap" -e operator="91461"  reg.docker.alibaba-inc.com/bootstrap/image:0.1

