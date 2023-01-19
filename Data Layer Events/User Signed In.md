# User Signed In

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Signed In",
    "user": {
        "institutionalID": "<institutionalID>",
        "loginMethod": "<loginMethod>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.institutionalID|string|Captures the ID used to login to the institutional site||||||||
|user.loginMethod|string|Captures if there was a user login to the website via a customized user name, account, or ID||||||||




