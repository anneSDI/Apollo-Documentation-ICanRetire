# Onsite Promo Click

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Onsite Promo Click",
    "linkInfo": {
        "customLinkName": "<customLinkName>"
    },
    "promotion": {
        "promoName": "<promoName>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkInfo.customLinkName|string|Name of the custom link that applies to a given click||||||||
|promotion.promoName|string|Captures the onsite promo that was clicked on by the user||||||||




