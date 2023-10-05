# 1. Webpage

第二次《设计工程学》的课程，主要讲授了网站搭建的相关步骤。利用html/markdown语言，本小组将过程数据同时储存在github及本地磁盘中（包括图片、文本等），并生成网页架构。 

## 1.1 环境配置
在Github上创建新Repository之后，将文件保存至本地磁盘。

用Visual Studio Code打开，按照如下步骤进行本地环境配置与初始化。

<head>
  <style>
    .center {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 20vh;
    }
  </style>
</head>
<body>
  <div class="center">
    <img src="https://github.com/ingw3216/blogimage/raw/main/img/20231005231359.png" alt="Fig1. Install docsify">
  </div>
</body>

<head>
  <style>
    .center {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 20vh;
    }
  </style>
</head>
<body>
  <div class="center">
    <img src="https://github.com/ingw3216/blogimage/raw/main/img/20231005231408.png" alt="Fig2. Initialize and preview">
  </div>
</body>

**遇到问题**：无法加载docsify.ps1，因为在此系统上禁止运行脚本

**解决方案**：管理员权限运行Powershell，输入Set-ExecutionPolicy -ExecutionPolicy RemoteSigned，更改脚本执行策略。


<head>
  <style>
    .center {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 20vh;
    }
  </style>
</head>
<body>
  <div class="center">
    <img src="https://github.com/ingw3216/blogimage/raw/main/img/20231005234205.png" alt="Fig3. Solution">
  </div>
</body>

## 1.2 Markdown语言

## 1.3 图片上传

小组采用了知乎用户@小小芋子的<a href="https://zhuanlan.zhihu.com/p/489236769">
建议</a>，在PicGo上将图片上传至专门Github的另一Repository内，通过Personal Access Tokens调用图片以减轻网页文件的负担。

![Github设置](https://github.com/ingw3216/blogimage/raw/main/img/20231005235445.png )

![Github设置](https://github.com/ingw3216/blogimage/raw/main/img/20231005235451.png )


## 1.4 视频上传

## 1.5 可待改进

## 1.6 Reference & Acknowledgment