# Tool Step Encountered

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Tool Step Encountered",
    "page": {
        "advisorID": "<advisorID>",
        "pageName": "<pageName>",
        "visitorID": "<visitorID>"
    },
    "tool": {
        "pollAnswer": "<pollAnswer>",
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
|page.advisorID|string|Captures the Advisor ID asssociated with user activity||||||||
|page.pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page.visitorID|string|Captures the Adobe Experience Cloud ID associated with user activity||||||||
|tool.pollAnswer|string|Captures the user's sentiment poll answer||||||||
|tool.processStepLabel|string|Captures the tool process step name||||||||
|tool.processStepValue|string|Captures the tool process step number||||||||
|tool.selfServiceActivityName|string|Captures the name of the self-service activity that the user started or completed||||||||
|tool.settingUsed|string|The setting used when running an application\/tool||||||||
|tool.toolId|string|Unique identifier of a site tool|Mortgage Calculator|||||||




