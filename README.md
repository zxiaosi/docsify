> 🎊 Docsify 模板，下载即用

### 1. Docsify 安装及初始化

+ 全局安装 `docsify-cli` 工具，可以方便地创建及在本地预览生成的文档。

  ```sh
  npm i docsify-cli -g
  ```

+ 新建文件夹（名字、位置随意），进入到文件夹，并初始化

  ```sh
  # 我的文件在e盘下docs
  e:			# 进入到e:
  cd docs			# 进入到文件夹
  docsify init		# 初始化
  ```

+ 初始化成功后，可以看到 `./docs` 目录下创建的几个文件

  - `index.html` 入口文件
  - `README.md` 会做为主页内容渲染
  - `.nojekyll` 用于阻止 GitHub Pages 忽略掉下划线开头的文件

### 2. Docsify 服务启动

+ 通过运行 `docsify serve` 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 [http://localhost:3000](http://localhost:3000/)

  ```sh
  docsify serve
  ```

### 3. 克隆

+ 克隆仓库或者下载仓库文件
+ 将 `doc` 内的文件替换 `./docs` 目录下的文件（刚刚创建的文件夹）
+ 启动 Docsify 服务，访问 [http://localhost:3000](http://localhost:3000/) 即可看到
+ `index.html` 就是配置文件

### 4. 推荐一下我写的文章 😋

+ [Docsify笔记搭建](https://hexo.xiaosi.world/archives/f8fffde8.html)
+ [Docsify 进阶配置](https://hexo.xiaosi.world/archives/cd1d42d1.html)