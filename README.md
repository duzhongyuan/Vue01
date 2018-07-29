# Vue01
学习Vue.js的第一个项目，采用Vue2.0版本。

# 使用方法
* 安装vue-cli
	使用npm(需要安装node环境)全局安装webpack，打开命令行工具输入:`npm install -g webpack webpack-cli`，安装完成之后输入`webpack -v`，如果出现相应的版本号，则说明安装成功。

	注意：从webpack 4.x开始，需要安装webpack-cli依赖，所以使用这条命令`npm install -g webpack webpack-cli`
* 全局安装vue-cli
	在cmd中输入命令，`npm install --global vue-cli`，安装完成之后输入`vue -V`，如果出现相应的版本号，则说明安装成功。
* 用vue-cli来构建项目
	首先创建一个文件夹(vueproj)作为项目存放地，然后使用命令行cd进入到项目目录输入`vue init webpack vue01`，vue01是自定义的项目名称，命令执行之后，会在当前目录生成一个以该名称命名的项目文件夹。
* 进入该项目名称目录，执行安装依赖的命令:`npm install`
	( 如果安装速度太慢。可以安装淘宝镜像，打开命令行工具，输入：
 npm install -g cnpm --registry=https://registry.npm.taobao.org
 然后使用cnpm来安装 )

* 启动项目
	`npm run dev`

* 打包上线
	`npm run build`







