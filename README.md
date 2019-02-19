# iOS Media Library-features record, encode, decode, filter, play etc.

## 主播端

* 视频采集 AVFoundation(原生) GPUImageVideoCamera(第三方SDK)

    * 音频采集 AVFoundation(原生)

    * 视频处理 GPUImage美颜、水印等（第三方SDK）

    * 音视频编码压缩

* 软编码

    * 视频软编码（H.264，MPEG）（第三方SDK）
    * 音频软编码（MP3，AAC）（第三方SDK）

* 硬编码

    * 视频硬编码（VideoToolbox）（iOS原生）
    * 音频硬编码（AudioToolbox）（iOS原生）

* 推流

    * 音频封装（FLV或TS格式）
    * 协议（RTMP、HLS、FLV）
    * 数据推送

## 服务端

* 数据分发（CDN）
* 截屏
* 录制
* 转码

## 用户端

* 拉流（RTMP、HLS、FLV）
* 解码（软解码、硬解码）
* 播放（ijkPlayer）





