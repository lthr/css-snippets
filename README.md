# CSS snippets

### Making sure images have alternative text.

Fix from: https://mobile.twitter.com/AllThingsSmitty/status/930617039085035520

Guide: https://axesslab.com/alt-texts/

```css
img[alt=""],
img:not([alt]) {
  border: 5px dashed #c00;
}
```

### jQuery animate CSS classes

```javascript
var el = $('.some-class');
el.addClass('animate');
setTimeout(function () {
  el.removeClass('animate');
}, 200);
```
