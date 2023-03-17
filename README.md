This warehouse mainly stores the configuration files of the services used by my own home server

Service list:

- `bark`: push message, basically any service that can configure webhook can configure it
- `code-server`: web-side `vscode`, basically useless, out of curiosity
- `ddns-go`: update dns resolution, home broadband ip will be updated automatically
- `download-tool`: Only Thunder is used for downloading, `alist` is convenient for devices to use through `webdav`
- `drone`: do `ci`, but it is not recommended to deploy `drone` and `gitea` together, `oauth` is more difficult to do
- `mariadb`: the database for these services
- `netdisk`: `nextcloud` as network disk, `photoprism` photo preview service
- `redis`: cache
- `snapdrop`: Similar to `airdrop`, devices with different platforms at home can quickly share files through this
- `traefik`: reverse proxy