# 欢迎大家使用呼研所李时悦课题组的服务器
# 这个主要是给大家介绍一下我们这个服务的一些信息和给不熟悉服务器的小伙伴们一点检验，欢迎大家提出意见和指点

## 1. 获取服务器账号密码
相信你们已经获得了服务器的账号和密码了
如果没有服务器账号密码的小伙伴们可以联系lzk_linzikai@163.com ，仅限本课题组的同学哦

## 2. 已有服务
服务器已经安装了R 4.4.0 和 python 3.12.3
服务器网络是通过校园网访问的，有时可能被校园网踢下线了，可以联系管理员 lzk_linzikai@163.com

## 3. 建议

# 不给用本地向服务器传输大文件！！等一下我腾讯云欠费了就找你！

### 3.1 miniconda
推荐在服务器安装安装miniconda，这个可以帮助你们控制环境和r包，毕竟服务器的R包是全空白的哦

https://docs.anaconda.com/free/miniconda/

``` bash
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh # 这个要自己看一下下载文件的链接进行修改
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh

# 更新bash shell
~/miniconda3/bin/conda init bash

# 重新进入服务器
```

### 3.2 R
推荐先装miniconda再使用r

如果你是在学校的用户，安装完miniconda可以直接在本地浏览器中使用内网IP:8787进入R，使用自己账号密码就可以登录 （内网IP：10.158.160.111）

如果你是在学校外的用户，安装完miniconda可以直接在本地浏览器中使用外网IP:8787进入R，使用自己账号密码就可以登录 （外网ip：不告诉你）

### 3.3 文件传输
建议使用外网ip登录的小伙伴，不要从本地直接上传文件到服务器，因为是通过腾讯云的服务器进行流量转发的，每个月只有200g，还是个3M的小水管 (T ^ T) ，用超了我就去找你(≖ᴗ≖)✧

内网的你就随便传，校园网网速巨快 （内网IP：10.158.160.111）


### 3.4 python 
建议你直接在本地装vscode连服务器玩，你都会这个了其他应该也不用我教(￣▽￣)~*
