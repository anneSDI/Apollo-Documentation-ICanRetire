# Video Chapter Click

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Video Chapter Click",
    "video": {
        "chapterClicked": "<chapterClicked>",
        "videoName": "<videoName>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|video.chapterClicked|string|Name of the chapter of the video that was clicked||||||||
|video.videoName|string|Video Name|Twitch\_FPS, Age of Empires, Halo|||||||




