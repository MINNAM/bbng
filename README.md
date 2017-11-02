# bbng
A javascript library for a parallax effect

##### HTML

```HTML

<div class='foo' style='background-image: url("./path/to/image1.jpg");'></div>
<div class='foo' style='background-image: url("./path/to/image2.jpg");'></div>
<div class='foo' style='background-image: url("./path/to/image3.jpg");'></div>

```
##### JS
```HTML
<script src = './bbng.js'></script>
<script>

var bbng = new BBNG({ className : 'foo', offset: 0.6 });

window.onload = function() {

	bbng.render();

}
</script>

```
