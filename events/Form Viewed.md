# Form Viewed

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Form Viewed",
    "form": {
        "formID": "<formID>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|formID|string|Unique identifier of a form. |F-0113, 2543, CU001, PI-0988|||||||
