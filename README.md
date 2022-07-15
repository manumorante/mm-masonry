# MM Masonry Photo Gallery

![image](https://user-images.githubusercontent.com/3266486/170789547-9fcfa677-01b0-4347-9d6a-941cc34efd21.png)

## Demo

[Demo: CSS Grid + custom props](https://masonry.manumorante.com/web/01-css-grid-custom-props.html)

## Config the **column width** and **gap**

Using css selector:

```css
.mm-masonry {
  --_col-width: 240;
  --_gap: 8;
}
```

Or directly in the html tag:

```html
<div class="mm-masonry" style="--_gap: 20">...</div>
```

## Disable option

You can control the disable option by using the following css selector:

```css
.mm-masonry {
  --_display: block; /* unset | flex | ...*/
  --_gap: 0; /* Or a value */
}
```

## Using some JavaScript

**CSS Grid + image load event**

Set image dimensions when `onload` event in Javascript.

[Demo: CSS Grid + image load event](https://masonry.manumorante.com/web/02-css-grid-js-load.html)

## CSS columns

The simplest way: with CSS Columns.

[Demo: CSS columns](https://masonry.manumorante.com/web/03-css-colums.html)
