# cloud-music-manager
nas(群晖)音乐管理器,配合**music-tag-web**,**navidrome**,**音流**使用

## Features

- [ ] 支持telegram交互
- [ ] 支持docker部署和Github Action
- [ ] 根据平台下载音乐解锁程序(自动)
- [ ] 搜索
  - [ ] 网易云
  - [ ] youtube
  - [ ] soundcloud
- [ ] 下载
  - [ ] 网易云链接
  - [ ] youtube链接
  - [ ] soundcloud链接
- [ ] 整理
    - [ ] 音乐库重复性判断(自动)
    - [ ] 音乐解锁(自动)
    - [ ] 支持手动修改音乐标签
    - [ ] 上传到nas(自动)

## telegram命令

- `/search` 搜索音乐.接受音乐关键字,支持网易云音乐,youtube,soundcloud
- `/download` 下载音乐并解锁.接受音乐链接,支持网易云音乐,youtube,soundcloud
- `/tidy` 整理音乐并入库.接受音乐链接,包括下载,解锁(如需),去重,上传等一系列操作