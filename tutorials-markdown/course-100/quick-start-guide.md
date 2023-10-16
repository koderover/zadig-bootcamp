summary: ZadigX 新手快速入门课程 T100
id: t100
categories: training
environments: Web
status: Published
authors: Martin Liu
Feedback Link:  https://github.com/koderover/zadig-bootcamp/issues

# ZadigX 新手快速入门课程 T100
<!-- ------------------------ -->


## 准备环境
Duration: 2

### 概述

前提条件：

1. 已经收到了 ZadigX 团队为本培训课程注册学员提供的系统访问账号，并已经能正常登录。
2. 将示例代码 Fork 到个人账户中，为变更这套代码做好准备。
3. 在 GitLab 中创建用于代码仓库集成接入的应用认证秘钥。

### 示例应用代码

本课程基于一套可以运行的云原生微服务系统，该应用系统的架构图如下：

![系统架构图](images/2023-10-16_22-35-34.jpg)

* 前端：只有一个页面，该页面上现实两条动态的信息：前端程序构建的时间戳，后端服务构建的时间戳（通过调用后端 /api/buildstamp 接口获得）
* 后端：运行在 20219 端口上，有几个简单的示例 api 组成。
* 前后端是松耦合的结构，前后端开发人员可以在同一套环境中各自独立开发迭代。

代码库位于：<https://gitlab.com/martinliu/zadig-training.git>

操作说明：

1. 访问并登录 [GitLab](https://gitlab.com) 个人账户。
2. 将示例代码库 Fork 到自己的账户中。

### 创建 GitLab 集成秘钥

参考文档：<https://docs.koderover.com/zadig/ZadigX%20v1.7.0/settings/codehost/gitlab/>

创建成功的应用认证秘钥，如下图所示：

![GitLab Auth key](images/2023-10-16_23-01-57.jpg)

将 `Application ID` 和 `Secret` 复制在写字板中备用。

### 验收检查

1. 个人 GitLab 账户中具有 `zadigx-training` 示例代码库。
2. 创建好的 GitLab 应用集成秘钥对。

点击 NEXT 进入下一步。

<!-- ------------------------ -->
## 初始化项目
Duration: 3

To indicate how long each slide will take to go through, set the `Duration` under each Heading 2 (i.e. `##`) to an integer. 
The integers refer to minutes. If you set `Duration: 4` then a particular slide will take 4 minutes to complete. 

The total time will automatically be calculated for you and will be displayed on the codelab once you create it. 

<!-- ------------------------ -->
## 定义代码构建
Duration: 5

To include code snippets you can do a few things. 
- Inline highlighting can be done using the tiny tick mark on your keyboard: "`"
- Embedded code

### JavaScript

```javascript
{ 
  key1: "string", 
  key2: integer,
  key3: "string"
}
```

### Java

```java
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```

<!-- ------------------------ -->
## 首次调试服务
Duration: 5

### 网址链接格式

同 markdown 的标准写法。

[Youtube - Halsey Playlists](https://www.youtube.com/user/iamhalsey/playlists)

### 插入图片

同 markdown 的标准写法。

[alt-text-here](assets/Puppy.JPG)

<!-- ------------------------ -->
## 修复已知 Bug
Duration: 5

访问 Codelab 官方的格式化文档说明: [Codelab Formatting Guide](https://github.com/googlecodelabs/tools/blob/master/FORMAT-GUIDE.md)



<!-- ------------------------ -->
## 管理自动化测试
Duration: 5

访问 Codelab 官方的格式化文档说明: [Codelab Formatting Guide](https://github.com/googlecodelabs/tools/blob/master/FORMAT-GUIDE.md)


<!-- ------------------------ -->
## 发布新版本
Duration: 5


<!-- ------------------------ -->
## 扩展补充练习
Duration: 5
