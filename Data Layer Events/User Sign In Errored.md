# User Sign In Errored

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Sign In Errored",
    "user": {
        "custKey": "<custKey>",
        "loginMethod": "<loginMethod>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|user.loginMethod|string|Captures if there was a user login to the website via a customized user name, account, or ID||||||||




