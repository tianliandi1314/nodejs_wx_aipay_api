# 个人支付免签系统 Api 版本

  技术栈 eggJs + mysql + Vue

  项目说明： 解决个人网站收款，见视频教程 https://pan.baidu.com/s/1czuBjaTIT2hwC215yQ-FlQ

  支付Demo地址: http://pay.yio.me/#/goods/DwnNGCW4VLk1CjemIiUqf

  客户端地址： http://pay.yio.me/#/goods/74ct1zBzZBW8YGFBKe-Yf

注:安卓客户端不提供源代码，仅提供App安装文件;
  
### 最后一次更新 2019-01-19 19:51:15

  1. 解决支付宝二维码生成限制，无需上传支付宝二维码;

  2. 增加视频教程;

## 文本教程

  1. 安装 node.js mysql 环境，并将此项目所有文件下载到服务器任意目录上面；

  2. 进入项目根目录,找到 config/config.default.js 文件按照提示修改所需配置， 进入database/config.js 文件修改 development 数据量连接信息；

  3. 在根目录中打开命令行， 执行 npm i 安装依赖文件；

  4. 在根目录中打开命令行， 执行 npx sequelize db:migrate  创建数据表结构, 注： 是npx 不是 npm；

  5. 在根目录中打开命令行， 执行 npm start 启动应用,默认端口7001，npm stop 停止应用;

  6. 访问 http://你的服务器地址:端口号/index.html 


## Api文档

  下载本项目后，进入DocApi目录，使用浏览器打开index.html文件即可;

  你只需要关注 ↓

  order - 创建支付订单

  无需关注↓

  android - 接收推送客户端信息

  android - 验证客户端

  
