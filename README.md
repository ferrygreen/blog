# blog
这是一个测试用的博客网页。博客内容由[hexo](https://hexo.io/zh-cn/)生成，主题为[next](http://theme-next.iissnan.com/)。master分支为源码，gh-pages分支为hexo自动生成、部署的今天网页文件。
> [Ferry的小屋](http://ferrygreen.top/)


## 使用步骤：  
&emsp;&emsp;安装Hexo相当简单。然而在安装前，您必须检查电脑中是否已安装下列应用程序：   
  + [Node.js](http://nodejs.org/)
  + [git](https://git-scm.com/) &emsp;&emsp;&emsp;&emsp;#发布到guthub上面，如果只是本地体验不需要
  

  1. 安装hexo：  
  ```Bash
  $ npm install -g hexo-cli #安装hexo
  ```
  2. 安装hexo依赖模块
  ```Bash
  $ npm install  #安装hexo依赖模块
  ```
  3. 安装插件：
  ```Bash
  $ npm install hexo-deployer-git --save #用于git发布上传
  $ npm install --save hexo-filter-flowchart #用于生成流程图
  $ npm install --save hexo-filter-sequence #用于生成序列图
  $ npm install hexo-generator-searchdb --save #用于生成站内搜索
  $ npm install hexo-generator-feed --save #用于生成RSS
  $ npm install --save hexo-helper-live2d #向你的Hexo里放上一只萌萌哒二次元看板娘!
  $ npm install live2d-widget-model-shizuku  #安装使用的live2d模型
  ```  
  4. 运行hexo即可：  
  ```Bash
  $ hexo server
  ```
