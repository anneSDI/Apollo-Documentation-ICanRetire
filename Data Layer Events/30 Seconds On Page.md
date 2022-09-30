# 30 Seconds On Page

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "30 Seconds On Page",
    "page": {
        "advisorID": "<advisorID>",
        "siteName": "<siteName>",
        "visitorID": "<visitorID>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page.advisorID|string|Captures the Advisor ID asssociated with user activity||||||||
|page.siteName|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|page.visitorID|string|Captures the Adobe Experience Cloud ID associated with user activity||||||||




