# Article Click

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Article Click",
    "content": {
        "contentTitle": "<contentTitle>"
    },
    "linkInfo": {
        "customLinkName": "<customLinkName>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|content.contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||
|linkInfo.customLinkName|string|Name of the custom link that applies to a given click||||||||




