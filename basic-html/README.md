## Content Middle

```css
.app {
  width: 140px;
  margin: auto;
}
```

or <b>Margin top bottom with specific size</b>

```css
.app {
  width: 140px;
  margin: 30px auto;
}
```

## Auto fix Text scroll in mobile size and desktop use "max-width"

```css
.app {
  max-width: 140px;
}
```

## Clear Float

```css
.clr {
  clear: both;
}
```

this properties clear float both left and right when one card overlap to other card

then use

```html
<div class="clr"></div>
```

## li item show horizontally

```css
.app {
  float: left;
}
```

if background are gone then use <b>overflow: auto</b> properties in parent class

The <b>overflow</b> property specifies whether to clip the content or to add scrollbars when the content of an element is too big to fit in the specified area.
