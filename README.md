<div align="center"><img src="card.svg"></div>

<div align="center"><h1>neteasemusic-github-profile</h1></div>

<div align="center">🎵 将你最近听的歌显示在 github profile 上 🎵</div>

## 使用方法：

### `Fork` 一份此仓库或者自己新建一个仓库

### 1. 获取网易云音乐用户 `id`

![image](https://user-images.githubusercontent.com/31311826/133114645-1a27d063-971d-4ede-9775-52f8052ef655.png)

然后修改 [main.yml](https://github.com/Nthily/netease-music-card/blob/main/.github/workflows/main.yml#L21) 中的 `USER_ID`

### 2. 获取网易云音乐用户的 `TOKEN`
 * 打开网页控制台，找到 Application 下 Cookie 为 `MUSIC_U` 的值
![}QV)3FH9@L9LUJ({35JJI}M](https://user-images.githubusercontent.com/31311826/133136019-63bbf232-d8d0-469d-8a45-f46fffdbeaab.png)
 * 打开自己项目中的设置，找到 `Secrets` 新建一个名为 `USER_TOKEN` 的 `Secrets`
 ![image](https://user-images.githubusercontent.com/31311826/133136507-fb2b61f8-1c09-40b8-bb7e-90e3f43b2c55.png)
 * 将第一步获取到的值粘贴进去

### 3. 修改 `main.yml`
 将 [main.yml](https://github.com/Nthily/netease-music-card/blob/main/.github/workflows/main.yml#L24) 中的 `AUTHOR` 修改为自己的 Github 用户名即可

### 4. 引用图片

最后只需要在你的 github profile 仓库添加图片链接即可

`[card](https://github.com/你的 Github 用户名/netease-music-card/blob/main/card.svg)`

你也可以使用 [Jsdelivr](https://www.jsdelivr.com/?docs=gh) CDN 来引用图片

`[card](https://cdn.jsdelivr.net/gh/你的 Github 用户名/netease-music-card/card.svg)`
