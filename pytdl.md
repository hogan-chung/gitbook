# Pytdl Python的YTDL!

***

目前有五種功能~~

| 方法 | 傳回參數 |
| :-----: | :-----: |
| `getVideo(url)` | dict |
| `getAudio(url)` | dict |
| `getVideoList(list_url)` | dict |
| `getAudioList(list_url)` | dict |
| `download(stream, path)` | none |

Video 的相關功能會回傳影片資訊
Audio 則不會
Video/Audio 皆有的屬性有:

- **stream**
- **url**
- **id**

List 的相關功能是以個別影片的 ID 為 Key, 可以用以下方法獲得

```py
for id in List:
  print(List[id])
```