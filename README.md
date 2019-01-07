## prepare
```
npm init -y
npm install babel-cli babel-register babel-preset-es2015 babel-preset-stage-2 --save-dev
```
### 根目录下创建 `.babelrc`
```
{
	"presets": ["es2015","stage-2"]
}
```
```
node_modules/.bin/babel server/index.js -o server/index.babel.js
```