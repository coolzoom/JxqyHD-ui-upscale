# 剑侠情缘 月影传说 HD版 UI upscale
- 用AI软件对界面进行高清放大，20210228，更改architectural为art模式，色彩就不会那么尖锐了

### 使用方式
- 右上角点code->downloadzip然后解压，打开复制里面所有内容到游戏目录覆盖原有文件

### todo
- todo, 对应法术和物品图标大小尚未调整
- todo, 对应顶部按钮功能后弹窗位置尚未调整
- todo, 部分asf转换时软件崩溃，effect里面几个文件暂未处理 只做大小缩放不做AI修复 
- mag006-1-蚀骨血仞.asf mag006-3-蚀骨血仞.asf mag008-1-潮起月盈.asf mag009-3-云生结海.asf mag016-3-烈火情天.asf mag025-1-冰刀攻击.asf mag030-1-魂牵梦绕.asf 蔷薇攻击.asf
- todo 法术效果已经处理暂不替换，位置需要做调整


### 20210302 对话窗体批量3倍AI高清放大
- MpcAsfTool修改支持批量导入放大后的图片，感谢@mapic91大佬 https://github.com/coolzoom/jxqyMpcAsfTool
<img align="center" src="https://github.com/coolzoom/JxqyHD-ui-upscale/blob/master/Snipaste_2021-03-02_15-39-23.png" alt="1" />

### 20210228 游戏底部界面和按钮3倍AI高清放大
<img align="center" src="https://github.com/coolzoom/JxqyHD-ui-upscale/blob/master/Snipaste_2021-02-28_21-32-33.png" alt="1" />

### 20210227 动态主界面，需配合提交https://github.com/coolzoom/JxqyHD/commit/0522f821852f8db18327a6cbc92dc85aaf37798f
- 备注：大图貌似只能插入10帧否则报错，可能是文件大小限制
<img align="center" src="https://github.com/coolzoom/JxqyHD-ui-upscale/blob/master/Snipaste_2021-02-27_17-05-54.png" alt="1" />

### 20210227 art模式重新生成主界面和按钮
<img align="center" src="https://github.com/coolzoom/JxqyHD-ui-upscale/blob/master/Snipaste_2021-02-27_15-35-21.png" alt="1" />

### 20210227 游戏顶部界面和按钮3倍AI高清放大
<img align="center" src="https://github.com/coolzoom/JxqyHD-ui-upscale/blob/master/Snipaste_2021-02-27_15-01-29.png" alt="1" />

### 20210227 存档界面和按钮3倍AI高清放大
- todo, 字体大小未调整, 使用gameedit启动和直接jxqy启动生成的存档图大小不一样
<img align="center" src="https://github.com/coolzoom/JxqyHD-ui-upscale/blob/master/Snipaste_2021-02-27_14-05-30.png" alt="1" />

### 20210227 主界面和按钮3倍AI高清放大
<img align="center" src="https://github.com/coolzoom/JxqyHD-ui-upscale/blob/master/Snipaste_2021-02-27_00-08-37.png" alt="1" />

### 逐帧修复过场动画
- 因原动画画质过低，以及XNA 限制，修复效果不佳



# 地址和工具链接

### 游戏主程序
- 主源 https://github.com/mapic91/JxqyHD
- 发布帖 https://tieba.baidu.com/p/3548082633
- 下载 https://pan.baidu.com/s/1skOIS81

### MpcAsf动画工具
- 主源 https://github.com/mapic91/MpcAsfTool
- 发布贴 https://tieba.baidu.com/p/2703334080
- 下载 https://pan.baidu.com/s/1kVb9N

### map地图工具
- 主源 https://github.com/mapic91/MapTool
- 发布贴 https://tieba.baidu.com/p/2934537815
- 下载 https://pan.baidu.com/s/1skHsovN

### wmv转换工具 必须在winxp下运行。选single pass 格式
- encode360 https://www.videohelp.com/software/Encode360
- 依赖项 https://www.free-codecs.com/windows_media_encoder_9_series_download.htm

# XNA支持格式

- 1) Video enabled with Digital Rights Management cannot be used.
- 2) Video must be encoded to the Windows Media Video 9 "Main" profile by using the VC-1 standard.
- 3) Video must be encoded with a constant bit rate (CBR).
- 4) Video must include an audio track.
- 5) Audio accompanying the video must be Windows Media Audio (.wma) encoded, with a single-pass CBR format.
- 6) XNA Game Studio supports the following maximum bit rates: 

|Level          |Maximum Bit Rate          |Representative resolutions by frame rate   |
|:--------------|:-------------------------|:-----------------------------------------:|
|Low            |2 Mbps                    |320 × 240 @ 24 Hz (QVGA)                   |
|Medium         |10 Mbps                   |720 × 480 @ 30 Hz (480p)                   |
|Medium         |10 Mbps                   |720 × 576 @ 25 Hz (576p)                   |
|High           |20 Mbps                   |1280 × 720 @ 30 Hz (720p)                  | 