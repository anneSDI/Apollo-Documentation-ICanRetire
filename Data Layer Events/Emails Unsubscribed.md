# Emails Unsubscribed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Emails Unsubscribed",
    "subscription": {
        "subscriptionType": "<subscriptionType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|subscription.subscriptionType|string|Describes the type of subscription. |news, updates, sales, events|||||||




