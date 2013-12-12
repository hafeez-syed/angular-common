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
    
    /**
        Or you can toggle multiple modules with the /modules/common/common.js file.
        angular.module('app', [
            'common.master'
        ]);
    */

})();
```

## Suggestions 
For new suggestions please create an issue so I can keep track of all suggestions.

Title your issue like this:

`(TYPE) MESSAGE`

`(request) Foobar module`

TYPE:
- request: new module
- idea: new layout or technique for the overall project
- upgrade: an existing module
