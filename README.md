# MenuToggler-JavaScript
Easiest way to toggle mobile main navigation or submenu open / close with vanilla JavaScript.

```javascript
<script>
function openMenu() {
  var element = document.getElementById("menu");
  element.classList.toggle("show");
}
function openSubmenu(el) {
  el.classList.toggle("open");
  el.parentNode.querySelector('ul').classList.toggle("show");
}
</script>
```
