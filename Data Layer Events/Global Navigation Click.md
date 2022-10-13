# Global Navigation Click

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Global Navigation Click",
    "linkInfo": {
        "customLinkName": "<customLinkName>",
        "linkId": "<linkId>"
    },
    "navigation": {
        "menuName": "<menuName>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkInfo.customLinkName|string|Name of the custom link that applies to a given click||||||||
|linkInfo.linkId|string|Identifier of the link clicked|act now, cancel, ok, 3456, 8765|||||||
|navigation.menuName|string|Captures the name of the menu or panel used to navigate the site||||||||




