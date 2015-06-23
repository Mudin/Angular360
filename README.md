# Angular360

360 degree panorama VR library for AngularJS. [Sample](http://ejeinc.github.io/Angular360/)

## Install

```
$ bower install angular360
```

or, simply [download](https://github.com/ejeinc/Angular360/archive/master.zip) and include `angular360.css` and `angular360.js` files.

## Example HTML.

```HTML
<!DOCTYPE html>
<html ng-app="myApp">
<head>
  <title>Angular360</title>
  <!-- Include CSS -->
  <link rel="stylesheet" type="text/css" href="bower_components/angular-360/angular360.css">
</head>
<body>
  <!-- Put <vr-cube> element -->
  <vr-cube front="img/front.jpg" left="img/left.jpg" right="img/right.jpg" back="img/back.jpg" top="img/top.jpg" bottom="img/bottom.jpg"></vr-cube>

  <!-- Include dependencies -->
  <script src="bower_components/angular/angular.min.js"></script>

  <!-- Include JS -->
  <script src="bower_components/angular-360/angular360.js"></script>
  <script type="text/javascript">
    // Add 'Angular360' to your module dependencies
    angular.module('myApp', ['Angular360']);
  </script>
</body>
</html>
```

## License

MIT
