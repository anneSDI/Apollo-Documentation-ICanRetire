# Download Link Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Download Link Clicked",
    "linkInfo": {
        "fileName": "<fileName>",
        "linkId": "<linkId>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkInfo.fileName|string|Indicates the filename for download link tracking.|Year End 2012.pdf, Operating Instructions.doc`|||||||
|linkInfo.linkId|string|Identifier of the link clicked|act now, cancel, ok, 3456, 8765|||||||




