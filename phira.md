如何连接lyyh0的Phira多人服务器
=

### 注意：本人不推荐你使用该服务器，建议去选别的多人服务器

#### 安装服务

1.  下载[termux](https://github.com/termux/termux-app/releases/latest)

2.  输入`pkg install cloudflared`并运行，输入y并回车安装

#### 运行服务并连接服务器

1.  在termux里输入`cloudflared access tcp --hostname phira.lyyh0.cloudns.be --listener localhost:10000`并运行

2.  在Phira多人服务器里写上`localhost:10000`

3.  启动`多人游戏`选项并点击出来的小球，点击连接即可

### 注意：不推荐使用本服务器，如果你不知道在哪里找，[可以点我去看看](https://phira.dmocken.top/Multiplayer%20Server)
