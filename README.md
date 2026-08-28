<div align="center">

# hlsay-emoticons

一个面向博客评论区使用的 **OwO 格式表情包合集**，目前主要用于 [Artalk](https://github.com/ArtalkJS/Artalk) 评论系统。

[![OwO](https://img.shields.io/badge/format-OwO-ff69b4)](https://github.com/DIYgod/OwO)
[![Artalk](https://img.shields.io/badge/Artalk-compatible-2ea44f)](https://artalk.js.org/zh/guide/frontend/emoticons.html)
[![jsDelivr](https://img.shields.io/badge/CDN-jsDelivr-orange)](https://www.jsdelivr.com/)

</div>

## 简介

`hlsay-emoticons` 是一个个人整理与维护的表情包配置仓库。核心文件 [`hlsay.json`](./hlsay.json) 使用 OwO 表情包数据格式，将多组常用 Emoji 与图片表情集中在一个配置中，方便在 Artalk 等兼容 OwO 格式的项目里直接加载。

目前包含以下分组：

- Emoji
- 小黄脸
- 小电视
- 贴吧
- 抖音
- 小红书
- 小黑盒
- 热词系列
- 2233娘
- QQ
- 钉钉

> README 仅展示每个分组中的少量预览，完整内容请以 [`hlsay.json`](./hlsay.json) 为准。

## 在 Artalk 中使用

Artalk 原生兼容 OwO 格式的远程表情包文件，可以直接使用本仓库通过 jsDelivr 提供的地址：

```text
https://cdn.jsdelivr.net/gh/yellow13441/hlsay-emoticons/hlsay.json
```

### Artalk 配置文件

在 `artalk.yml` 中配置：

```yaml
frontend:
  emoticons: https://cdn.jsdelivr.net/gh/yellow13441/hlsay-emoticons@main/hlsay.json
```

### 前端配置

也可以在 `Artalk.init` 中动态加载：

```js
Artalk.init({
  // ...
  emoticons: 'https://cdn.jsdelivr.net/gh/yellow13441/hlsay-emoticons@main/hlsay.json',
})
```

更多用法请参考 [Artalk 表情包文档](https://artalk.js.org/zh/guide/frontend/emoticons.html#%E8%A1%A8%E6%83%85%E5%8C%85)。

## 表情包预览

### Emoji

😀 😃 😄 😁 😅 🤣 😂 🙂 🙃 🫠 😉 😊 😇 🥰 😍

### 小黄脸

<p>
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/BiliBili/%E5%B0%8F%E9%BB%84%E8%84%B8/doge_%E9%87%91%E7%AE%8D.png" width="52" alt="doge 金箍" title="doge 金箍">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/BiliBili/%E5%B0%8F%E9%BB%84%E8%84%B8/%E7%AC%91%E5%93%AD.png" width="52" alt="笑哭" title="笑哭">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/BiliBili/%E5%B0%8F%E9%BB%84%E8%84%B8/%E8%B9%B2%E8%B9%B2.png" width="52" alt="蹲蹲" title="蹲蹲">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/BiliBili/%E5%B0%8F%E9%BB%84%E8%84%B8/%E6%98%9F%E6%98%9F%E7%9C%BC.png" width="52" alt="星星眼" title="星星眼">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/BiliBili/%E5%B0%8F%E9%BB%84%E8%84%B8/%E5%BE%AE%E7%AC%91.png" width="52" alt="微笑" title="微笑">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/BiliBili/%E5%B0%8F%E9%BB%84%E8%84%B8/%E5%90%83%E7%93%9C.png" width="52" alt="吃瓜" title="吃瓜">
</p>

### 小电视

<p>
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibilitv/1.png" width="52" alt="小电视 1">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibilitv/10.png" width="52" alt="小电视 2">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibilitv/11.png" width="52" alt="小电视 3">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibilitv/12.png" width="52" alt="小电视 4">
</p>

### 贴吧

<p>
  <img src="https://twikoo-magic.oss-cn-hangzhou.aliyuncs.com/Tieba-New/image_emoticon.png" width="52" alt="贴吧 1">
  <img src="https://twikoo-magic.oss-cn-hangzhou.aliyuncs.com/Tieba-New/image_emoticon10.png" width="52" alt="贴吧 2">
</p>

### 抖音

<p>
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/Douyin/weixiao.png" width="52" alt="微笑" title="微笑">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/Douyin/aimu.png" width="52" alt="色" title="色">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/Douyin/liangdai.png" width="52" alt="呆住" title="呆住">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/Douyin/kuye.png" width="52" alt="生气" title="生气">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/Douyin/koubi.png" width="52" alt="抠鼻" title="抠鼻">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/Douyin/wulian.png" width="52" alt="捂脸" title="捂脸">
</p>

### 小红书

<p>
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/RedNote/%E5%BE%AE%E7%AC%91.png" width="52" alt="微笑" title="微笑">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/RedNote/%E5%AE%B3%E7%BE%9E.png" width="52" alt="害羞" title="害羞">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/RedNote/%E5%A4%B1%E6%9C%9B.png" width="52" alt="失望" title="失望">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/RedNote/%E6%B1%97%E9%A2%9C.png" width="52" alt="汗颜" title="汗颜">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/RedNote/%E5%93%87.png" width="52" alt="哇" title="哇">
  <img src="https://cdn.jsdmirror.com/gh/Augenstern-O/Stickers/RedNote/%E5%96%9D%E5%A5%B6%E8%8C%B6.png" width="52" alt="喝奶茶" title="喝奶茶">
</p>

### 小黑盒

<p>
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/Heybox/expression_cube.png" width="52" alt="Heybox 1">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/Heybox/expression_cube_bingbujiandan.png" width="52" alt="Heybox 2">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/Heybox/expression_cube_bizui.png" width="52" alt="Heybox 3">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/Heybox/expression_cube_cangsang.png" width="52" alt="Heybox 4">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/Heybox/expression_cube_dalian.png" width="52" alt="Heybox 5">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/Heybox/expression_cube_doge.png" width="52" alt="Heybox 6">
</p>

### 热词系列

<p>
  <img src="https://twikoo-magic.oss-cn-hangzhou.aliyuncs.com/bilibiliHotKey/1.jpg" width="110" alt="热词 1">
  <img src="https://twikoo-magic.oss-cn-hangzhou.aliyuncs.com/bilibiliHotKey/10.jpg" width="110" alt="热词 2">
  <img src="https://twikoo-magic.oss-cn-hangzhou.aliyuncs.com/bilibiliHotKey/11.jpg" width="110" alt="热词 3">
  <img src="https://twikoo-magic.oss-cn-hangzhou.aliyuncs.com/bilibiliHotKey/12.jpg" width="110" alt="热词 4">
  <img src="https://twikoo-magic.oss-cn-hangzhou.aliyuncs.com/bilibiliHotKey/13.jpg" width="110" alt="热词 5">
</p>

### 2233娘

<p>
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibili2233/1.png" width="64" alt="2233娘 1">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibili2233/10.png" width="64" alt="2233娘 2">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibili2233/11.png" width="64" alt="2233娘 3">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibili2233/12.png" width="64" alt="2233娘 4">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/bilibili2233/13.png" width="64" alt="2233娘 5">
</p>

### QQ

<p>
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/QQ/0.gif" width="52" alt="QQ 1">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/QQ/1.gif" width="52" alt="QQ 2">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/QQ/10.gif" width="52" alt="QQ 3">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/QQ/100.gif" width="52" alt="QQ 4">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/QQ/101.gif" width="52" alt="QQ 5">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/QQ/102.gif" width="52" alt="QQ 6">
</p>

### 钉钉

<p>
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/dingtalk/emotion_001.png" width="52" alt="钉钉 1">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/dingtalk/emotion_002.png" width="52" alt="钉钉 2">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/dingtalk/emotion_003.png" width="52" alt="钉钉 3">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/dingtalk/emotion_004.png" width="52" alt="钉钉 4">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/dingtalk/emotion_005.png" width="52" alt="钉钉 5">
  <img src="https://cdn.jsdelivr.net/gh/2x-ercha/twikoo-magic@master/image/dingtalk/emotion_006.png" width="52" alt="钉钉 6">
</p>

## OwO 格式

本仓库的 `hlsay.json` 使用 [DIYgod/OwO](https://github.com/DIYgod/OwO) 所采用的表情包数据结构。Artalk 已原生兼容 OwO 格式，因此无需额外转换即可通过 URL 动态加载。

一个简化后的结构大致如下：

```json
{
  "Emoji": {
    "type": "emoji",
    "container": [
      {
        "icon": "😀",
        "text": "😀"
      }
    ]
  },
  "示例图片表情": {
    "type": "image",
    "container": [
      {
        "icon": "<img src='https://example.com/example.png'>",
        "text": "示例"
      }
    ]
  }
}
```

## 更新与缓存

`hlsay.json` 更新后，jsDelivr 可能仍会在一段时间内返回缓存版本。如果刚刚提交了修改但线上暂未变化，可以稍后重新检查，或使用 jsDelivr 的缓存刷新工具处理对应 URL。

如果用于需要严格固定内容的生产环境，也可以指定 Git Tag 或 Commit，例如：

```text
https://cdn.jsdelivr.net/gh/yellow13441/hlsay-emoticons@<tag-or-commit>/hlsay.json
```

## 相关项目与文档

- [Artalk 表情包文档](https://artalk.js.org/zh/guide/frontend/emoticons.html#%E8%A1%A8%E6%83%85%E5%8C%85) — Artalk 表情包配置、OwO 格式兼容与动态加载说明
- [ArtalkJS/Artalk](https://github.com/ArtalkJS/Artalk/tree/master) — 自托管评论系统
- [DIYgod/OwO](https://github.com/DIYgod/OwO) — OwO 表情与 Emoji 输入插件及其数据格式

## 素材与版权说明

本仓库主要用于整理表情包配置。`hlsay.json` 中的部分图片资源来自第三方仓库、CDN 或相关平台素材，例如：

- [Augenstern-O/Stickers](https://github.com/Augenstern-O/Stickers)
- [2X-ercha/Twikoo-Magic](https://github.com/2X-ercha/Twikoo-Magic)

相关表情图片、角色形象、品牌名称及其他素材的版权归各自原作者、平台或权利人所有。本仓库不对第三方素材主张所有权，仅用于个人博客及相关项目中的表情配置整理与展示。

如有版权或资源引用方面的问题，可通过 Issue 联系处理。

## Contributing

欢迎提交 Issue 或 Pull Request：

- 补充新的表情包分组
- 修复失效的图片地址
- 修正表情名称或配置格式
- 优化 Artalk / OwO 的兼容性

提交修改时，请尽量保持 `hlsay.json` 为合法 JSON，并确认新增图片链接能够通过 HTTPS 正常访问。

---

如果这个仓库对你的 Artalk 配置有所帮助，欢迎 Star ⭐
