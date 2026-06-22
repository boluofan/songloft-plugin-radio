# songloft-plugin-radio

Songloft JS 插件 —— 从 M3U/M3U8 播放列表文件导入电台到 Songloft。

## 功能

- 支持本地文件上传或远程 URL 获取 M3U/M3U8 文件
- 解析 Simple M3U、Extended M3U（`#EXTINF`）、IPTV 扩展属性（`tvg-name`/`tvg-logo`/`group-title`）
- 自动检测并拒绝 HLS 媒体播放列表（切片列表），仅接受频道列表
- 预览解析结果，支持全选/反选
- 批量导入到指定电台歌单，支持新建歌单
- 推荐资源：[m3u-radio-music-playlists](https://github.com/junguler/m3u-radio-music-playlists)

## Development

```bash
npm install
npm run dev         # watch + auto-upload to local Songloft
npm run build       # produce dist/radio.jsplugin.zip
npm run validate    # verify plugin.json hashes
```

## Author

Songloft Team

## License

Apache-2.0 © 2026 Songloft Team
