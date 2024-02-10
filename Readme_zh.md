**[English](README.md) | 简体中文**

<h1 align="center"><a href="" target="_blank" rel="noopener noreferrer"><img width="250" src="https://www.swarmcloud.net/img/logo.png" alt="cdnbye logo"></a></h1>
<h4 align="center">Save Your Bandwidth using WebRTC.</h4>
<h4 align="center">视频网站省流量&加速插件.</h4>
<p align="center">
  <a href="https://www.npmjs.com/package/cdnbye-shaka"><img src="https://img.shields.io/npm/v/cdnbye-shaka.svg?style=flat" alt="npm"></a>
  <a href="https://www.jsdelivr.com/package/npm/cdnbye-shaka"><img src="https://data.jsdelivr.com/v1/package/npm/cdnbye-shaka/badge" alt="jsdelivr"></a>
</p>

## 优势
- 浏览器原生支持，不需要安装任何插件，采用仿BT算法，在线人数越多效果越好
- 支持基于HLS流媒体协议(m3u8)的直播和点播场景
- 支持基于MPEG-DASH流媒体协议的直播和点播场景
- 支持加密传输
- 浏览器不支持WebRTC时无缝切换到HTTP下载模式
- 高可配置化，用户可以根据特定的使用环境调整各个参数
- 支持video.js、Clappr、DPlayer等第三方播放器
- 通过有效的调度策略来保证用户的播放体验以及p2p率
- Tracker服务器根据访问IP的ISP、地域等进行智能调度

## 快速入门
将[quick-start.html](demo/quick-start.html)拷贝到您的网页中并运行。再打开另一个相同的网页。见证奇迹的时候到了！您已在两个网页之间建立了一个P2P连接，在不安装任何插件的情况下。如果在这个频道中（一个mpd标识了一个频道）没有其它参与者，那么您打开的第一个网页将作为种子为第二个网页提供数据。

## 浏览器支持情况
由于WebRTC已成为HTML5标准，目前大部分主流浏览器都已经支持。CDNBye的浏览器兼容性取决于WebRTC和Shaka Player。

兼容性|Chrome | Firefox | Mac Safari| 安卓微信/QQ | Opera | Edge | IE | iOS Safari |
:-: | :-: | :-: | :-: | :-: | :-: | :-:| :-:| :-:
WebRTC | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ❌ | ✔ |
Shaka | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ❌ |
CDNBye | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ❌ | ❌ |

## 集成
通过script标签引入最新版本：
```html
<script src="https://cdn.jsdelivr.net/npm/cdnbye-shaka@latest"></script>
```

## API文档
参见 [API.md](https://www.cdnbye.com/cn/shaka/API.html)

## 后台管理系统
在接入P2P插件后，访问`https://www.cdnbye.com/oms`，注册并绑定域名，即可查看该域名的P2P流量、在线人数、用户地理分布等信息。

## 相关项目
- [hlsjs-p2p-engine](https://gitee.com/cdnbye/hlsjs-p2p-engine) - HLS协议的Web端P2P流媒体方案。
- [dashjs-p2p-engine](https://github.com/cdnbye/dashjs-p2p-engine) - MPEG-dash协议的Web端P2P流媒体方案。
- [mp4-p2p-engine](https://github.com/cdnbye/mp4-p2p-engine) - 支持MP4的Web端P2P流媒体方案。

## FAQ
我们收集了一些[常见问题](https://www.cdnbye.com/faq.html)。在报告issue之前请先查看一下。

## 联系我们
邮箱：service@cdnbye.com


