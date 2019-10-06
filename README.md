









[youtube-dl/README.md at master · ytdl-org/youtube-dl · GitHub](https://github.com/ytdl-org/youtube-dl/blob/master/README.md#readme)

```bash

##仅下载播放列表 一行一个json 仅有简要信息
youtube-dl -j --flat-playlist https://www.youtube.com/playlist?list=PLPZy-hmwOdEX7M4fJRlPjFMpQBFwvFPDw > playlist.txt
##下载播放列表 -i 忽略错误
youtube-dl -j   -i https://www.youtube.com/playlist?list=PLPZy-hmwOdEX7M4fJRlPjFMpQBFwvFPDw > playlist.txt

## 下载字幕  
youtube-dl --write-sub --sub-lang zh-Hans,en  --write-auto-sub   --skip-download  -i   https://www.youtube.com/playlist?list=PLPZy-hmwOdEX7M4fJRlPjFMpQBFwvFPDw

##下载画质最好视频
youtube-dl -i https://www.youtube.com/playlist?list=PLPZy-hmwOdEX7M4fJRlPjFMpQBFwvFPDw

## 使用代理下载
youtube-dl --proxy=192.168.0.2:10809 -f  bestvideo+bestaudio https://www.youtube.com/playlist?list=PLgGXSWYM2FpPw8rV0tZoMiJYSCiLhPnOc


```

