# Moving-cloud
 It is a mobile cloud application that contains only css.   Simple animated cloud application that will add color to your application.



## An animated application made with jquery using simple css and js.

### Inspired by a cloud application made. Similar but mobile and shaped app.
## Usage

```js
 var cloudWidth = $(".cloud").width();
    function cloudHeight() {
      $(".cloud").css({ 'height': cloudWidth + 'px' });
    };
    $(document).ready(function () {
      cloudHeight();
    });
    $(window).resize(function () {
      cloudWidth = $(".cloud").width();
      cloudHeight();
    });
```





<img src="blutu.PNG">
