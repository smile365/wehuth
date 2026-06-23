# wehuth

wechat Hugo theme - wehuth.
微信公众号文章风格的 Hugo 主题，[Demo](https://sxy91.com)

## Quick Start

From the root of your Hugo site, clone the theme into `themes/wehuth` by running:

```sh
# Clone theme into the themes/wehuth directory
$ git clone https://github.com/smile365/wehuth.git themes/wehuth
```

then

```sh
# test with draft posts
$ hugo server -D -t wehuth --bind=0.0.0.0 --baseURL=http://127.0.0.1:1313
```

## Configuration

Please see the sample [`config.toml`](https://github.com/smile365/wehuth/blob/master/exampleSite/config.toml).

### Params

| Param | Type | Default | Description |
|-------|------|---------|-------------|
| `home_path` | string | — | 首页显示的分类路径，如 `/categories/life` |
| `author` | string | — | 作者名 |
| `subtitle` | string | — | 副标题（显示在头像旁） |
| `description` | string | — | 站点描述 |
| `keywords` | string | — | 站点关键词 |
| `license` | string | — | 版权声明（HTML） |
| `adsense_publisher_id` | string | — | Google AdSense publisher ID（不含 `pub-` 前缀） |
| `baidu_analytics` | string | — | 百度统计 HM ID |
| `ga4` | string | — | Google Analytics 4 Measurement ID（如 `G-XXXXXXXXXX`） |
| `valine_appId` | string | — | Valine 评论系统 appId |
| `valine_appKey` | string | — | Valine 评论系统 appKey |
| `enableToc` | bool | `true` | 是否启用文章目录（仅 ≥400 字的文章显示） |
| `enableReadingTime` | bool | `true` | 是否显示阅读时间 |
| `image.url` | string | — | OG/Twitter 卡片默认图片 URL |
| `github` | string | — | GitHub 链接 |
| `wechat` | string | — | 微信链接 |
| `zhihu` | string | — | 知乎链接 |

## Features

- 微信公众号排版风格（640px 居中）
- SEO：JSON-LD 结构化数据、Open Graph、Twitter Card
- 暗色模式（跟随系统 `prefers-color-scheme`）
- 响应式布局
- 分页页码显示
- 文章分类/标签
- 文章目录（TOC）
- 上一篇/下一篇导航
- 阅读时间统计
- 多语言支持（i18n：中文/英文）
- Google AdSense / 百度统计 / Google Analytics（可配置）
- Valine 评论系统（可配置）
- 打印友好样式

## Thanks

Thanks to the following projects I learned from:

* wechat stylesheet [wechat-mp-article](https://github.com/ufologist/wechat-mp-article)
* Hugo theme [nuo](https://github.com/smile365/hugo-nuo)
* hugo theme [KeepIt](https://github.com/Fastbyte01/KeepIt)

## License

Licensed under the MIT License. See the [LICENSE](https://github.com/smile365/wehuth/blob/master/LICENSE) file for more details.
