# Self Service Starts

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Self Service Starts",
    "tool": {
        "processStep": <processStep>,
        "processStepLabel": "<processStepLabel>",
        "processStepValue": "<processStepValue>",
        "selfServiceActivityName": "<selfServiceActivityName>",
        "settingUsed": "<settingUsed>",
        "toolId": "<toolId>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|tool.processStep|boolean|Indicates the user encountered a prcess step||||||||
|tool.processStepLabel|string|Captures the tool process step name||||||||
|tool.processStepValue|string|Captures the tool process step number||||||||
|tool.selfServiceActivityName|string|Captures the name of the self-service activity that the user started or completed||||||||
|tool.settingUsed|string|The setting used when running an application\/tool||||||||
|tool.toolId|string|Unique identifier of a site tool|Mortgage Calculator|||||||




