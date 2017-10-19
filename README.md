# Gulp 前端项目构建最佳实践 

> 1. 建立站点文件夹
	-  1.1 开发环境，src 文件夹
	-  1.2 生产环境，build文件夹
	-  1.3 Gulp环境搭建  : npm install —-save-dev gulp

> 2. 开发环境向生产模式输出
	-  2.1 清空（删除）文件夹 : del
	-  2.2 复制文件  :  src -> dest
	-  2.3 LESS文件编译  :  gulp-less
	-  2.4 CSS合并 : gulp-concat
	-  2.5 CSS压缩 : gulp-clean-css 
	-  2.6 JS ES6 -> ES5  : gulp-babel
	-  2.7 JS合并 : gulp-concat
	-  2.8 JS压缩 : gulp-uglify , 文件改名： gulp-rename
	-  2.9 图片压缩 : gulp-imagemin
    -  2.10 雪碧(Sprite Image)图 / 精灵图 : gulp-css-spriter : jpg, png 
    -  2.11 base64 : gulp-base64


> 3. 浏览器（服务器） 同步：
	-  3.1 建立服务器 : browser-sync 
	-  3.2 浏览器实时刷新  browser对象的.reload


> 4. Gulp项目自动化配置
	-  4.1 路径统一修改&配置
	-  4.2 版本控制 gulp-rev , gulp-rev-collector
	-  4.3 Gulp操作流程控制 gulp-notify
	-  4.4 Gulp项目通知



> 5. Gulp前端构建最佳实践： 

	- 5.1  开发环境： 一旦启动了开发环境的服务器，修改任何一个开发环境下的文件， 服务器自动同步效果
	- 5.2  生产环境： 一旦启动了生产环境的服务器，生产环境自动更新开发环境部署的新版本， 复制所有的必要文件， 并且处理好所有的路径问题






