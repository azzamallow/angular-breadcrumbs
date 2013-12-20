angular-breadcrumbs
===================

Simple breadcrumbs directive which will generate markup based on the $location path

install
-------

```
bower install angular-breadcrumbs
```

usage
-----

Make sure you include the module in your application config

```
angular.module('myApp', [
  'breadcrumbs',
  ...
]);
```

Insert the directive anywhere in your html view

```
<breadcrumbs></breadcrumbs>
```

If bootstrap is included the directive will be styled for you already, however this is not required for the directive to work
