# Tabler Icons

A set of over 300 free MIT-licensed high-quality SVG icons for you to use in your web projects. Each icon is designed on a 24x24 grid and a `2px` stroke.

```
npm install tabler-icons --save
```

## Preview

![](./.github/icons.svg)


## Usage

All icons are built with SVG, so you can place them as `<img>`, `background-image` and inline in HTML code.

### HTML image

If you load an icon as an image, you can modify its size using CSS.

```html
<img src="path/to/icon.svg" alt="icon title"/>
```

### Inline HTML

You can paste the content of the icon file into your HTML code to display it on the page. 

```html
<a href="">
  <svg xmlns="http://www.w3.org/2000/svg" 
    class="icon tabler-icon tabler-icon-disabled" 
    width="24" height="24" viewBox="0 0 24 24" 
    stroke-width="1.25" stroke="currentColor" fill="none" 
    stroke-linecap="round" stroke-linejoin="round">
      ...
  </svg>
  Click me
</a>
```

Thanks to that, you can change the size, color and the `stroke-width` of the icons with CSS code.

```css
.icon-tabler {
  color: red;
  width: 32px;
  height: 32px;
  stroke-width: 1.25;
}
```

### SVG sprite

Add an icon to be displayed on your page with the following markup (`activity` in the above example can be replaced with any valid icon name):

```html
<svg width="24" height="24">
  <use xlink:href="path/to/tabler-sprite.svg#tabler-activity"/>
</svg>
```

## Multiple strokes

All icons in this repository have been created with the value of the `stroke-width` property, so if you change the value, you can get different icon variants that will fit in well with your design.

![](./.github/icons-stroke.svg)

## License

Tabler Icons is licensed under the [MIT License](https://github.com/tabler/tabler-icons/blob/master/LICENSE).
