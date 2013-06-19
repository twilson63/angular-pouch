# Angular-Pouch

An AngularJS module and bower package wrapper around the nightly build of pouchDb.

The purpose of this module is to make it super easy to install and upgrade web applications to the latest pouchDb.

## html

``` html
<script src="/components/pouchdb-nightly.min/index.js"></script>
<script src="/components/angular/angular.js"></script>
<script src="/components/angular-pouch/angular-pouch.js"></script>
```

## angular app

``` js
angular.module('App', ['angular-pouch'])
  .constant($db, $pouch('idb://mydbname'));
```

## contribute

Pull requests are welcome.


## License

MIT

