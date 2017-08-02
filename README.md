# Gulp

### 命令安装及插件

  第一步：

    淘宝镜像的安装：

    	命令:  npm install -g cnpm --registry=https://registry.npm.taobao.org

    	淘宝镜像包管理工具：开头 cnpm

    	包管理工具（国外）：npm

    Gulp命令安装与检测：

      1）全局安装：$ npm install --global gulp  (缩写: $ npm i -g gulp)

      2）局部安装：$ npm install --save-dev gulp  (缩写: $ npm i -S gulp)

      3）在根目录创建 gulpfile.js 文件：

         var gulp = require('gulp');

         gulp.task('default',function() {

            //写一条输出代码，比如：

            console.log("hello word!");

         });

      4）检测(运行Gulp)：$ Gulp

 ### HTML、CSS、JS 插件：

    1.gulp-connect

    	命令: npm install --save-dev gulp-connect

    	cnpm i -S gulp-connect

    2.gulp-htmlmin

    	命令: npm i gulp-htmlmin --save-dev

    	cnpm i -S gulp-htmlmin

    3.gulp-less

    	命令: npm install gulp-less

    	cnpm i -S gulp-less

    4.gulp-path

    	命令: npm install gulp-path

    	cnpm i -S gulp-path

    5.gulp-sass

    	命令: npm install gulp-sass --save-dev

    	cnpm i -S gulp-sass

    6.gulp-stylus

    	命令: npm install --save-dev gulp-stylus

    	cnpm i -S gulp-stylus

    7.gulp-cssmin

    	命令: npm install --save-dev gulp-cssmin

    	cnpm i -S gulp-cssmin

    8.gulp-rename

    	命令: npm install  gulp-rename

    	cnpm i -S gulp-rename

    9.gulp-del

    	命令: npm install --save del

    	cnpm i -S del

    10.gulp-concat

    	命令: npm install --save-dev gulp-concat

    	cnpm i -S gulp-concat

    11.gulp-babel

    	命令: npm install --save-dev gulp-babel

    	cnpm i -S gulp-babel

    12.gulp-sourcemaps

    	命令: npm install gulp-sourcemaps

    	cnpm i -S gulp-sourcemaps

    13.gulp-uglify

    	命令: npm install --save-dev gulp-uglify

    	cnpm i -S gulp-ugfily

    14.gulp-eslint

    	命令: npm install gulp-eslint

    	cnpm i -S gulp-eslint

    15.gulp-imagemin

    	命令: npm install --save-dev gulp-imagemin

    	cnpm i -S gulp-imagemin

    16.imagemin-pngquant

    	命令: npm install --save imagemin-pngquant

    	cnpm i -S imagemin-pngquant