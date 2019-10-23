<!--
 * @Author: LiangJQ
 * @Date: 2019-10-11 22:40:06
 * @Description: 
 -->
# gulu191011
这是一个造轮子demo----Vue UI 组件

 ## 安装
 使用本框架前，请在css中开启boxder-box
 ```
 *{box-sizing: border-box;}
 ```

 ## 运行
 parcel index.html  --no-cache



 ## 过程
 - 设置淘宝源  npm install -g cnpm --registry=https://registry.npm.taobao.org
 - 设置淘宝源 sudo npm config set registry https://registry.npm.taobao.org/
 - 安装node_sass     SASS_BINARY_SITE=https://npm.taobao.org/mirrors/node-sass/ npm install node-sass
 - 安装打包工具parcel    npm install -g parcel-bundler
 - 运行   ./node_modules/.bin/parcel index.html --no-cache
 
 - 工具 
 - npm i -g git-open  安装后可直接用git open命令打开git提交页面

 ### 单元测试chai.js与mock
 > BDD---Behavior Driven Development  行为驱动开发
 > TDD---Test-Driven Development      测试驱动开发
 > Assert --  断言  console.assert()

 - 安装chai   npm i -D chai
 - npm i -D chai-spies

 ### 1、自动化测试
 - 使用 Karma + Mocha做单元测试

### 2、持续集成

### 3、重写所有的代码

### 4、发布npm包

### 5、完善README.MD
