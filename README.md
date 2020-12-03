# 秋水专刊

http://events.jackpu.com

## Run

``` bash
$ npm install && gulp
```


+ [Portfolio-个人简历](./profile)
+ [实现类似 Pinterest 的图片预加载功能](./pinterest-like-image-loading)
+ [实现类似 Medium 的图片预加载功能](./medium-like-image-loading)
+ [字体模糊](./blur-font)
+ [日本之行](./japan)
+ [Media Source Extensions](./media-source)
+ [JS 获取视频 Codec](./js-get-codec)
补充信息 ：
H265 H264 ：
1.这种视频编码格式 只存在于MP4中
https://baike.baidu.com/item/H.264/1022230
https://baike.baidu.com/item/H.265/7752521
2.有个现成的库，原理是扫描整个文件然后获取视频文件信息
（因为用户可以随意修改文件后缀原因，所有文件都会进行判断）通过codec判断，codec为hevc前缀即视为h265。[图片]后面这段是版本号
https://www.npmjs.com/package/mp4box
