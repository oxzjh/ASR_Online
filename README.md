# ASR Online

## 一、 接口
##### 1. 实时语音识别
- 说明：实时语音识别
- 路由地址：/asr/online
- 请求方式：POST
- Content-Type: application/json
- 参数：

|名称|类型|默认值|描述|
|-|-|-|-|
|save|bool|false|保存录音文件|
##### 2. VAD断句
- 说明：VAD断句
- 路由地址：/asr/vad
- 请求方式：POST
- Content-Type: application/json
- 参数：

|名称|类型|默认值|描述|
|-|-|-|-|
|frames|int|15|检测到frames帧定为有声音(每个样本60帧)|
|count|int|3|连续count个样本没声音则结束录音(每个样本0.6秒)|
|save|bool|false|保存录音文件|
##### <span id="/asr/download">3. 下载录音文件</span>
- 说明：下载录音文件
- 路由地址：/asr/download
- 请求方式：GET
- 参数：
无

## 二、测试


https://github.com/user-attachments/assets/f2e68fda-7332-4e00-9ba1-448b35265d23

