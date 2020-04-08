# HTML & CSS
## Chapter15: _Layout [Redux]_
- CSS departs from _"normal"_ or _"static"_ flow by employing **relative**, **absolute**, and **fixed** positioning schemes with the `position:` property and the **floating** positioning scheme with the `float:` property.
- Boxes can overlap with the `z-index:` property.
- `float:` [left, right, both, or none]
- If containing elements contain only floated elements, then assign values of  `overflow:` auto and `width:` 100%.
- Assign `width:`, `float:`, and `margin:` property values when creating multi-column layouts with floats.
- Fixed width layouts designs don't change size when browser window size is modified, and measurements are given in pixels.  Liquid layout designs change size in relation to browser window size modification, and measurements tend to use percentages.
- Multiple style sheets can be referenced in one HTML index page ... either (1) reference individual CSS style sheet with individual `href` properties within separate `<link>` elements or (2) use one `<link>` element and style sheet reference but add `@import` rule within that style sheet to reference multiple sheets.