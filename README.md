# 常用命令合集

一键复制常用命令，支持点击复制到剪贴板

演示地址：https://commands.937788.xyz/

## 目录

- [静态文件服务](#静态文件服务)
- [文件操作](#文件操作)
- [压缩解压](#压缩解压)
- [Git版本控制](#git版本控制)
- [Docker容器](#docker容器)
- [npm/Node.js](#npmnodejs)
- [网络相关](#网络相关)
- [Python相关](#python相关)
- [系统操作](#系统操作)
- [文件权限](#文件权限)
- [文本处理](#文本处理)
- [数据库](#数据库)

---

## 静态文件服务

| 命令 | 说明 | 环境 |
|------|------|------|
| `python -m http.server 8000` | Python 本地服务器（默认8000端口） | CMD/终端 |
| `python -m http.server 8080` | Python 指定端口 | CMD/终端 |
| `php -S localhost:8000` | PHP 本地服务器 | 终端 |
| `npx serve .` | npx 启动静态服务器 | 终端 |
| `npx serve -p 3000` | npx 指定端口 | 终端 |

## 文件操作

| 命令 | 说明 | 环境 |
|------|------|------|
| `find . -name "*.html"` | 查找所有 HTML 文件 | 终端 |
| `find . -name "*.jpg" -o -name "*.png" -o -name "*.gif"` | 查找所有图片文件 | 终端 |
| `ls -lhS` | 按大小排序查看文件 | 终端 |
| `wc -l *.html` | 统计文件行数 | 终端 |

## 压缩解压

| 命令 | 说明 | 环境 |
|------|------|------|
| `tar -cvf archive.tar ./folder` | 打包文件夹为 tar | 终端 |
| `tar -xzvf file.tar.gz` | 解压 tar.gz | 终端 |
| `zip -r archive.zip ./folder` | 压缩为 zip | CMD/终端 |
| `unzip file.zip` | 解压 zip | CMD/终端 |

## Git版本控制

| 命令 | 说明 | 环境 |
|------|------|------|
| `git init` | 初始化 Git 仓库 | CMD/终端 |
| `git clone https://github.com/user/repo.git` | 克隆仓库 | CMD/终端 |
| `git add .` | 添加所有文件到暂存区 | CMD/终端 |
| `git commit -m "提交信息"` | 提交更改 | CMD/终端 |
| `git push origin main` | 推送到远程仓库 | CMD/终端 |
| `git pull origin main` | 拉取最新代码 | CMD/终端 |
| `git status` | 查看仓库状态 | CMD/终端 |
| `git log --oneline` | 查看提交历史 | CMD/终端 |
| `git branch` | 查看分支 | CMD/终端 |
| `git checkout -b feature-branch` | 创建并切换新分支 | CMD/终端 |
| `git merge feature-branch` | 合并分支 | CMD/终端 |
| `git reset HEAD` | 撤销暂存的文件 | CMD/终端 |

## Docker容器

| 命令 | 说明 | 环境 |
|------|------|------|
| `docker --version` | 查看 Docker 版本 | 终端 |
| `docker ps` | 列出运行中的容器 | 终端 |
| `docker ps -a` | 列出所有容器 | 终端 |
| `docker images` | 列出本地镜像 | 终端 |
| `docker pull nginx:latest` | 拉取镜像 | 终端 |
| `docker run -d nginx:latest` | 运行容器（后台） | 终端 |
| `docker run -d -p 8080:80 nginx:latest` | 运行容器并映射端口 | 终端 |
| `docker exec -it container_id /bin/bash` | 进入容器交互式终端 | 终端 |
| `docker stop container_id` | 停止容器 | 终端 |
| `docker rm container_id` | 删除容器 | 终端 |
| `docker logs container_id` | 查看容器日志 | 终端 |
| `docker-compose up -d` | Docker Compose 启动 | 终端 |
| `docker-compose down` | Docker Compose 停止 | 终端 |

## npm/Node.js

| 命令 | 说明 | 环境 |
|------|------|------|
| `node -v` | 查看 Node.js 版本 | CMD/终端 |
| `npm -v` | 查看 npm 版本 | CMD/终端 |
| `npm init -y` | 初始化项目 | CMD/终端 |
| `npm install` | 安装项目依赖 | CMD/终端 |
| `npm install lodash` | 安装指定包 | CMD/终端 |
| `npm install -g package-name` | 全局安装包 | CMD/终端 |
| `npm install --save-dev webpack` | 安装开发依赖 | CMD/终端 |
| `npm run dev` | 运行项目脚本 | CMD/终端 |
| `npm start` | 启动项目 | CMD/终端 |
| `npm test` | 运行测试 | CMD/终端 |
| `npm uninstall lodash` | 卸载包 | CMD/终端 |
| `npm list` | 查看已安装的包 | CMD/终端 |

## 网络相关

| 命令 | 说明 | 环境 |
|------|------|------|
| `ping www.baidu.com` | 测试网络连接 | CMD/终端 |
| `curl https://api.example.com` | 发送 HTTP 请求 | 终端 |
| `curl -O https://example.com/file.zip` | 下载文件 | 终端 |
| `wget https://example.com/file.zip` | 使用 wget 下载 | 终端 |
| `ssh user@192.168.1.100` | SSH 远程连接 | 终端 |
| `scp file.txt user@server:/path/` | 远程复制文件 | 终端 |
| `netstat -tuln` | 查看网络端口状态 | 终端 |
| `ifconfig` | 查看 IP 地址 | 终端 |
| `ip addr` | 查看 IP 地址（新版） | 终端 |
| `nslookup www.baidu.com` | DNS 查询 | CMD/终端 |

## Python相关

| 命令 | 说明 | 环境 |
|------|------|------|
| `python --version` | 查看 Python 版本 | CMD/终端 |
| `python3 --version` | 查看 Python3 版本 | 终端 |
| `pip --version` | 查看 pip 版本 | CMD/终端 |
| `pip install requests` | 安装包 | CMD/终端 |
| `pip install -r requirements.txt` | 根据 requirements.txt 安装 | CMD/终端 |
| `pip uninstall requests` | 卸载包 | CMD/终端 |
| `pip list` | 列出已安装的包 | CMD/终端 |
| `pip freeze > requirements.txt` | 导出依赖到 requirements.txt | CMD/终端 |
| `python -m venv myenv` | 创建虚拟环境 | CMD/终端 |
| `jupyter notebook` | 启动 Jupyter Notebook | 终端 |
| `pip install --upgrade pip` | 升级 pip | CMD/终端 |

## 系统操作

| 命令 | 说明 | 环境 |
|------|------|------|
| `top` | 查看系统进程 | 终端 |
| `htop` | 交互式进程查看 | 终端 |
| `df -h` | 查看磁盘空间 | 终端 |
| `du -sh ./folder` | 查看目录大小 | 终端 |
| `free -h` | 查看内存使用情况 | 终端 |
| `lsblk` | 查看磁盘分区 | 终端 |
| `uname -a` | 查看系统信息 | 终端 |
| `whoami` | 查看当前用户 | CMD/终端 |
| `uptime` | 查看系统运行时间 | 终端 |
| `ps -aux` | 查看所有进程 | 终端 |
| `kill -9 process_id` | 终止进程 | 终端 |
| `killall process_name` | 按名称终止进程 | 终端 |
| `date` | 查看当前时间 | CMD/终端 |
| `cal` | 查看日历 | 终端 |
| `tasklist` | 查看进程（Windows） | CMD |
| `taskkill /F /PID process_id` | 终止进程（Windows） | CMD |

## 文件权限

| 命令 | 说明 | 环境 |
|------|------|------|
| `chmod +x script.sh` | 添加执行权限 | 终端 |
| `chmod 755 file.sh` | 设置 755 权限 | 终端 |
| `chmod 644 file.txt` | 设置 644 权限 | 终端 |
| `chmod -R 755 folder` | 递归设置目录权限 | 终端 |
| `chown user:group file` | 修改文件所有者 | 终端 |
| `chown -R user:group folder` | 递归修改目录所有者 | 终端 |
| `ls -l` | 查看文件权限详情 | 终端 |
| `stat file.txt` | 查看文件详细信息 | 终端 |

## 文本处理

| 命令 | 说明 | 环境 |
|------|------|------|
| `cat file.txt` | 查看文件内容 | 终端 |
| `head file.txt` | 查看文件前 10 行 | 终端 |
| `tail file.txt` | 查看文件后 10 行 | 终端 |
| `tail -f log.txt` | 实时查看日志 | 终端 |
| `grep "keyword" file.txt` | 搜索文件内容 | 终端 |
| `grep -r "keyword" ./folder` | 递归搜索目录 | 终端 |
| `wc -l file.txt` | 统计文件行数 | 终端 |
| `sort file.txt` | 排序文件内容 | 终端 |
| `uniq file.txt` | 去除重复行 | 终端 |
| `diff file1.txt file2.txt` | 对比两个文件 | 终端 |
| `sed 's/old/new/g' file.txt` | 替换文本内容 | 终端 |
| `awk '{print $1}' file.txt` | 处理文本列 | 终端 |
| `less file.txt` | 分页查看文件 | 终端 |
| `more file.txt` | 分页查看文件（传统） | 终端 |

## 数据库

| 命令 | 说明 | 环境 |
|------|------|------|
| `mysql -u root -p` | 登录 MySQL | CMD/终端 |
| `CREATE DATABASE dbname;` | 创建数据库 | CMD/终端 |
| `SHOW DATABASES;` | 查看所有数据库 | CMD/终端 |
| `USE dbname;` | 选择数据库 | CMD/终端 |
| `SHOW TABLES;` | 查看所有表 | CMD/终端 |
| `mysqldump -u root -p dbname > backup.sql` | 备份数据库 | CMD/终端 |
| `source backup.sql` | 导入数据库 | CMD/终端 |
| `redis-cli` | 连接 Redis | 终端 |
| `redis-cli -h host -p 6379` | 连接远程 Redis | 终端 |
| `redis-cli ping` | 测试 Redis 连接 | 终端 |
| `redis-cli keys '*'` | 查看所有 Key | 终端 |
