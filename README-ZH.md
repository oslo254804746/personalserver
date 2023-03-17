这个仓库 主要存放我自己家里服务器用到服务的配置文件

服务列表:

- `bark`:  推送消息, 基本上能配置webhook的服务都可以配置它
- `code-server`: web端`vscode`, 基本上没怎么用,出于好奇
- `ddns-go`: 更新dns解析, 家里宽带ip更换会自动更新
- `download-tool`: 下载只用到了迅雷, `alist`通过`webdav`方便设备使用
- `drone`: 做`ci`, 不过不建议`drone`和`gitea`部署在一起，`oauth`比较难搞
- `mariadb`: 这些服务的数据库
- `netdisk`:  `nextcloud`做网盘, `photoprism` 照片预览服务
- `redis`: 缓存
- `snapdrop`: 类似于`airdrop`，家里有不同平台的设备可以通过这个快速共享文件
- `traefik`: 反向代理



