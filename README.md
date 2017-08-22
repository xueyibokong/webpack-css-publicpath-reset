# webpack-css-publicpath-reset
	此插件是为了解决extract-text-webpack-plugin插件无法替换html中publicPath的问题
## 用法
	npm install webpack-css-publicpath-reset --save-dev
#### 代码中
	var webpackCssPublicpathReset = require('webpack-css-publicpath-reset');
	
	new webpackCssPublicpathReset({
        publicPath : 'http://css.example.com/project/css/'
    })