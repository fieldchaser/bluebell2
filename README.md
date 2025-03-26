# bluebell
bluebell是一个基于gin框架和Vue框架搭建的前后端分离的web项目。


## 技能清单

1. gin框架
2. zap日志库
3. Viper配置管理
4. swagger生成文档
5. JWT认证
6. 令牌桶限流
7. Go语言操作MySQL
8. Go语言操作Redis

### **解释**：
1. **前端部分**：
    - `npm install` 用于安装所有前端的依赖。
    - `npm run serve` 用于启动前端的开发服务器，通常会在 `localhost:8080` 上访问。

2. **后端部分**：
    - `docker build . -t bluebell_app` 用于构建后端的 Docker 镜像。
    - `docker-compose up` 用于启动 Docker 容器，启动时通常会把服务暴露在 `localhost:5000`，你可以根据需要调整配置文件。

这个 `README.md` 提供了基本的部署步骤，并且包含了前端和后端的详细部署方法，确保开发者能按照这些步骤顺利部署项目。

