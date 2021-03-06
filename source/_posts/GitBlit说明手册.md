---
title: GitBlit说明手册
date: 2017-02-20 09:52:53
tags:
		- 说明手册
---
# 安装
-  纯 Java 库用来管理、查看和处理 Git 资料库.相当于 Git 的 Java 管理工具.git的管家
   - [安装步骤][1] 

<!-- more -->

# 登录
  - `账户名：邮箱前缩写字母， 如：lichy/caizhp/`
  - `初始密码：123456`
  - [网址][2] 
  - 账户登录
    ![GitBlit-1.png](http://www.wailian.work/images/2018/09/09/GitBlit-1.png)
	
# 设置
  - 语言及克隆协议
![GitBlit-2.png](http://www.wailian.work/images/2018/09/09/GitBlit-2.png)

  - 添加SSH  Key
	-  本地Git已经注册  `·id_rs.pub 文件默认路径：C:\Users\Administrator\.ssh`
![GitBlit-3.png](http://www.wailian.work/images/2018/09/09/GitBlit-3.png)

# 服务器仓库
 - 新建服务器仓库 ：右上角  `new repository`
 - 克隆仓库至本地  : `git clone + 仓库地址  ` 

# 工作流程
  - git clone  默认是clone 的主分支（master）,一般我们都是在develop上提交代码 
  - 工作中重要问题，采用git commit 制作本地版本库，commit中格式要注意

``` stata
  	== Bug List ==

     * Fixed issue #1000 : 问题描述

     * Fixed issue #1001 : 问题描述

    == New List ==

     * Update :问题描述

     * Modify :问题描述

     * Add    :问题描述
```
# 配置
  - [配置文件][6]  : 包括工单配置、通知邮箱、成员

# 团队协作流程
  - 采用[Ticket模式][7]进行协作开发
 


  [1]: http://www.cnblogs.com/jeremylee/p/5626240.html
  [2]: http://192.168.2.208:10101/
  [3]: http://oimqf80rv.bkt.clouddn.com/GitBlit-1.png
  [4]: http://oimqf80rv.bkt.clouddn.com/GitBlit-2.png
  [5]: http://oimqf80rv.bkt.clouddn.com/GitBlit-3.png
  [6]: https://github.com/wisezhao/software/tree/master/GitBlitData
  [7]: http://www.cnblogs.com/x3d/p/gitblit-ticket.html
