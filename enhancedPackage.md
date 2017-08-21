其他主题增强包文件在主题文件包中。

主题增强包与主题完全独立，可以不使用。增强包的文件可以上传至服务器的任意位置。

### 网易云音乐歌单展示

![netease](https://ihewrocdn.b0.upaiyun.com/img/netease.png)

> 如何修改歌单数据？

打开`player.json`文件，里面填写你的歌单id,可填写多个，播放时会随机选取歌单播放。

```json
[
	"93931893",
    "722185666"
]
```

直接将整个`music`文件夹上传到你的服务器/主机上面

访问地址即：`./music`  （不要加上`index.php`否则访问错误）

【注意】：最后一个歌单id后不用加上英文逗号（,）

### 画廊相册

![photos](https://ihewrocdn.b0.upaiyun.com/img/photos.png)

> 如何修改照片数据？

图片存储在`user`文件夹下

打开`data.json`文件，模仿下面的格式，添加新的一行即可。

```json
[
  {
    "link": "./user/1.jpg",
    "h2": "大鱼海棠",
    "pTag": "大鱼海棠宣传图片"
  },
  {
    "link": "./user/2.jpg",
    "h2": "童年时光",
    "pTag": "童年时光"
  }
]
```

访问地址即`./album/index.php`

【注意】：最后一个图片信息块后不用加上英文逗号（,）