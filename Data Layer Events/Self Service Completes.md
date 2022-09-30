# Self Service Completes

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Self Service Completes",
    "tool": {
        "selfServiceActivityName": "<selfServiceActivityName>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|tool.selfServiceActivityName|string|Captures the name of the self-service activity that the user started or completed||||||||




