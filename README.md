# 🖼️ img

个人的图床仓库

## 配置步骤

1. 下载安装最新版 [PicGo](https://github.com/Molunerfinn/PicGo) [(Releases)](https://github.com/Molunerfinn/PicGo/releases)

2. 打开 PicGo 软件，添加本仓库为 GitHub 图床
   - 图床配置名: `Default` (可自定义)
   - 设定仓库名: `SlenderData/img`
   - 设定分支名: `main`
   - 设定 Token: `ghp_9a14****************************PtBW` (记在安全备忘里了)
   - 设定存储路径: `images/`

3. 安装 Node.js
   - 下载安装 [Node.js](https://nodejs.org/en/download/)
   - 安装完成后，打开命令行工具，输入 `node -v` 和 `npm -v`，如果能正确显示版本号，则安装成功

4. 安装配置 npm 上的 PicGo 图片重命名插件
   - 打开 PicGo 软件，打开插件设置
   - 搜索 `rename`，安装 liuwave 的 `rename-file 1.0.4`
   - 配置插件，设置文件(路径)格式为 `{y}/{m}/{d}/{h}-{i}-{s}-{hash}-{origin}-{rand:6}`
