# Tool Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Tool Started",
    "tool": {
        "processStep": <processStep>,
        "processStepLabel": "<processStepLabel>",
        "processStepValue": "<processStepValue>",
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
|tool.settingUsed|string|The setting used when running an application\/tool||||||||
|tool.toolId|string|Unique identifier of a site tool|Mortgage Calculator|||||||




