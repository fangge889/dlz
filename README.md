1. 确保 Hexo 已经安装
如果还没有安装 Hexo，可以使用以下命令进行全局安装：
npm install -g hexo-cli

2. 打开命令提示符或 PowerShell，运行以下命令来安装项目依赖：
npm install

3. 启动开发服务器
安装完依赖后，在相同的命令行窗口中运行以下命令来启动 Hexo 的开发服务器：
hexo server

启动服务器后，你可以在浏览器中访问 http://localhost:4000 来查看项目。

完整的操作步骤如下：
# 安装 Hexo CLI（如果未安装）
npm install -g hexo-cli
# 进入项目目录，安装项目依赖
npm install
# 生成静态文件 
hexo generate
# 部署你的网站
hexo deploy
# 清除缓存文件
hexo clean
# 启动开发服务器
hexo server