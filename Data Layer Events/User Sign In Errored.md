# User Sign In Errored

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Sign In Errored",
    "user": {
        "loginMethod": "<loginMethod>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.loginMethod|string|Captures if there was a user login to the website via a customized user name, account, or ID||||||||




