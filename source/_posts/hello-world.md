 # Helloworld

# Markdown

## Hexo的不完全教程
### 安装node和git

1.安装群里的node和git

### 使用npm安装hexo并启动

1.换源
```bash
 npm config set registry https://registry.npm.taobao.org
```

2.下载hexo-cli脚手架
```bash
 npm install -g hexo-cli
```

3.创建hexo项目
-在目标文件夹右键，在当前位置打开终端
```bash
hexo init <filename>
```

4.运行hexo项目
```bash
hexo server
```

5.markdown教程
[markdown教程](https://www.runoob.com/markdown/md-tutorial.html)

6.上传到GitHub并部署gitpage
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Ycsylph/Blogguide.git
git push -u origin main

```