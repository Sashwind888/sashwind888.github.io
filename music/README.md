# 音乐播放器配置文件说明

在这个目录下，你只需管理 `playlist.json` 即可配置播放器中的歌曲，无需修改任何代码文件！

## 格式示例 (`playlist.json`)

```json
[
  {
    "title": "歌曲名",
    "artist": "歌手名",
    "src": "./music/歌曲文件名.mp3",
    "cover": "https://图片链接 或 ./music/封面文件名.jpg"
  }
]
```

## 使用方法
1. 把你的 `.mp3` 音频文件复制到当前 `public/music/` 目录下。
2. 打开 `playlist.json`，在数组中填入对应的歌曲信息与文件名。
3. 网页会自动读取并生效。
