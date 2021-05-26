# Page Load Started

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "breadcrumbs": "<breadcrumbs>",
        "pageCategory": "<pageCategory>",
        "subsection": "<subsection>",
        "subsection2": "<subsection2>",
        "subsection3": "<subsection3>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|breadcrumbs|string|A delimited list of hierarchical sections that describe the current page's location within the navigation of the site.|Home>Women>Tops>Sweaters, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Checkout > Order Thank You|||||||
|pageCategory|string|General category or Site Section of the page. Top level of page hierarchy.|Home, About Us, Shop, Account, Blog, Investors|||||||
|subsection|string|First sub-level of hierarchy under pageCategory or Site Section. |Shop > Kids, Shop > Mens, Shop > Womens|||||||
|subsection2|string|Second sub-level of hierarchy under pageCategory or Site Section. |Shop > Kids > Tops, Shop > Mens > Shoes|||||||
|subsection3|string|Third sub-level of hierarchy under pageCategory or Site Section. |Shop > Kids > Tops > Tees, Shop > Mens > Shoes > Oxfords|||||||
