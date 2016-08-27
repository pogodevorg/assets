# WEB SVGS

Those SVGS are stripped and are meant to be inlined in HTML.
They use the following classes that need to be defined in CSS in order to fix the size and choose the fill color.

## Ball

For the `logo32web.svg` version:

* (svg)`.site-header-icon`: Top level svg logo element. You can use it to fix the size and `vertical-align` when used with the PogoDev text.
  * (path)`.svg-fill`: define the fill color or use `currentColor` to use current text color.

For the `logo216web.svg` version:

* (path)`.hero-logo-fill`: define the fill color or use `currentColor` to use current text color.

### Example

```css
.site-header-icon {
  width: 34px;
  height: 34px;
  vertical-align: middle;
  margin-right: 4.96577px;
  transition: transform .8s ease-in-out;
}
.svg-fill {
  fill: currentColor;
}
```

## PogoDev text

The PogoDev text using the [Roboto font](https://fonts.google.com/specimen/Roboto?selection.family=Roboto), converted to Outlines.

* (svg)`.site-header-title`: Top level svg element. You can use it to fix the size and `vertical-align` when used with the ball logo.
* You can also edit the `<title></title>` content to fit your needs.

### Example

```css
.site-header-title {
  width: 88px;
  height: 16px;
  vertical-align: middle;
}
```
