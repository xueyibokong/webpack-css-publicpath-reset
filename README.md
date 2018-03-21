# webpack-css-publicpath-reset
	此插件是为了解决extract-text-webpack-plugin插件无法替换html中publicPath的问题
## 用法
	npm install webpack-css-publicpath-reset --save-dev
#### 代码中
	var webpackCssPublicpathReset = require('webpack-css-publicpath-reset');
	
	new webpackCssPublicpathReset({
		includeLink : 'http://js.example.com/project/',
        publicPath : 'http://css.example.com/project/'	
    })
#### 参数说明
`publicPath` css要被替换为的路径。
`excludeLinks` 被匹配link上含有includeLink

