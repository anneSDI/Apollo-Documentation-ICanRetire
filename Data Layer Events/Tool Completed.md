# Tool Completed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Tool Completed",
    "tool": {
        "processStep": <processStep>,
        "processStepLabel": "<processStepLabel>",
        "processStepValue": "<processStepValue>",
        "selfServiceCompletes": <selfServiceCompletes>,
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
|tool.selfServiceCompletes|boolean|Indicates the user completed the self service process on the site.||||||||
|tool.toolId|string|Unique identifier of a site tool|Mortgage Calculator|||||||




