# Video Completed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Video Completed",
    "video": {
        "videoName": "<videoName>",
        "videoPlaytime": <videoPlaytime>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|video.videoName|string|Video Name|Twitch\_FPS, Age of Empires, Halo|||||||
|video.videoPlaytime|number|Amount of time the video has played||||||||




