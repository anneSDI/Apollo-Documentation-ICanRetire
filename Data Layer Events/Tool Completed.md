# Tool Completed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Tool Completed",
    "page": {
        "advisorID": "<advisorID>",
        "pageName": "<pageName>",
        "siteName": "<siteName>",
        "visitorID": "<visitorID>"
    },
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
|page.advisorID|string|Captures the Advisor ID asssociated with user activity||||||||
|page.pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page.siteName|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|page.visitorID|string|Captures the Adobe Experience Cloud ID associated with user activity||||||||
|tool.processStep|boolean|Indicates the user encountered a prcess step||||||||
|tool.processStepLabel|string|Captures the tool process step name||||||||
|tool.processStepValue|string|Captures the tool process step number||||||||
|tool.selfServiceCompletes|boolean|Indicates the user completed the self service process on the site.||||||||
|tool.toolId|string|Unique identifier of a site tool|Mortgage Calculator|||||||




