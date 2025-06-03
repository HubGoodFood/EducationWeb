# HTML网站部署到Render

这个项目包含一个简单的HTML网站，可以部署到Render云服务。

## 本地运行

1. 安装依赖:
```
npm install
```

2. 启动服务器:
```
npm start
```

3. 打开浏览器访问: `http://localhost:3000`

## 部署到Render

1. 创建Render账户: https://render.com
2. 点击 "New" > "Web Service"
3. 连接你的GitHub仓库或直接上传这个项目
4. 配置:
   - 名称: 你的选择
   - 环境: Node
   - 构建命令: `npm install`
   - 启动命令: `npm start`
5. 点击 "Create Web Service"

部署完成后，Render会提供一个URL访问你的网站。 