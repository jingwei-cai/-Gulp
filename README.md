# -Gulp
命令安装及插件
命令安装及插件
  第一步：
    Gulp命令安装与检测
      1）全局安装：$ npm install --global gulp  (缩写: $ npm i -g gulp)
      2）局部安装：$ npm install --save-dev gulp  (缩写: $ npm i -S gulp)
      3）在根目录创建 gulpfile.js 文件 ：
         var gulp = require('gulp');
         gulp.task('default',function() {
            //写一条输出代码，比如：
            console.log("hello word!");
         });
      4）检测(运行Gulp)：$ Gulp
HTML 插件
  安装：
CSS 插件
  Gulp-less安装：
JS 插件
  安装：