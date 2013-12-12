Angular JS Common
===========================

A collection of useful directives, filters, and services for Angular JS.

## Install

```
bower install angular-common
```

## Usage

```
(function() {

    'use strict';
    
    angular.module('app', [
        'common.api',
        'common.confirm',
        'common.dateRange',
        'common.drag',
        'common.mediaelement',
        'common.modal',
        'common.ngBindHtmlUnsafe',
        'common.print',
        'common.redactor',
        'common.strings',
        'common.time',
        'common.upload',
        'common.youtube'
    ]);

})();
```

Or instead of writing all of that out you can create a use a single reference by editing the /modules/common/common.js file which contains all the modules.


```
(function() {

    'use strict';

    angular.module('app', [
        'common.master'
    ]);
    
})();
```

## Roadmap

The long term vision for this project is to one by one elimnate all dependencies for this project and create completely angular based modules without the need for including external libraries.
