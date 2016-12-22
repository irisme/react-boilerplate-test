## 运行报错
1. 安装依赖 npm i
2. 编译运行 npm run start:production 
3. 进入 http://localhost:3000/test

## 使用0.4版react 没有bug
1. 将package.json 中的weui和react-weui的版本分别回到0.4.3和0.4.1
2. 安装依赖 npm i
3. 注释掉 app/app.js中 import 'react-weui/lib/react-weui.min.css'
4. 编译运行 npm run start:production 
5. 进入 http://localhost:3000/test
