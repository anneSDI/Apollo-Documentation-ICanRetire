# Article Click

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Article Click",
    "content": {
        "contentAction": "<contentAction>",
        "contentCategory": "<contentCategory>",
        "contentTitle": "<contentTitle>",
        "contentType": "<contentType>"
    },
    "linkInfo": {
        "customLinkName": "<customLinkName>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|content.contentAction|string|Content Action||||||||
|content.contentCategory|string|Content Category||||||||
|content.contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||
|content.contentType|string|Content Type||||||||
|linkInfo.customLinkName|string|Name of the custom link that applies to a given click||||||||




