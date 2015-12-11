Vanilla Javascript tooltip.
-------

Vanilla Javascript tooltip. Accepts plain text and fancy HTML.

#### Demo

[http://zoltantothcom.github.io/vanilla-js-tooltip](http://zoltantothcom.github.io/vanilla-js-tooltip)

#### Settings

Option | Type | Default | Description
------ | ---- | ------- | -----------
theme | string | dark | Selects one of the pre-defined tooltip styles - light or dark.
dist | number  | 10 | Specifies the distance in pixels from trigger to tooltip.
delay | number | 0 | Specifies how long the tooltip remains visible after the mouse leaves the trigger.

#### Example

HTML:

```html
Lorem <span data-tooltip="<img src='//lorempixel.com/150/100/' />" data-position="right top">ipsum</span> dolor sit amet.
```
Javascript:

```javascript
var tooltip = new Tooltip({
    theme: "dark",
    delay: 750
});
```

#### Browser support and dependencies

Browser | Support | Dependencies
------ | -------- | -----------
Chrome | yes | -
Firefox | yes | -
Safari | yes | -
Opera | yes | -
IE | yes* | -

\* _IE9 and up_

#### License

Free. [Unlicense](http://unlicense.org).
