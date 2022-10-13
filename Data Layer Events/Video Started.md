# Video Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Video Started",
    "video": {
        "startTime": "<startTime>",
        "videoName": "<videoName>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|video.startTime|string|How long in milliseconds it took the video to play||||||||
|video.videoName|string|Video Name|Twitch\_FPS, Age of Empires, Halo|||||||




