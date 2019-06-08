# Angular cheatsheet

Filters
- amount | currency[:symbol] - Formats a number as a currency (ie $1,234.56).
- any_date | date : format - Formats any_date with format  'dd MMM yyyy'

Directives
- ng-change="expression"
- ng-checked="boolean"
- ng-[dbl]click="expression"
- ng-model="expression"
- ng-repeat="([key,] value) in object|array"
- option ng-selected="boolean"
- ng-submit="expression"
- ng-hide|show="boolean"
- ng-if/ng-unless
- ng-disabled="boolean"

Components
- angular.module() defines a module
- Module.controller() defines a controller
- Module.directive() defines a directive
- Module.filter() defines a filter
- Module.service() or Module.factory() or Module.provider() defines a service
- Module.value() defines a service from an existing object Module
- ng-app attribute sets the scope of a module
- ng-controller attribute applies a controller to the view
- $scope service passes data from controller to the view
- $filter service uses a filter
- ng-app attribute sets the scope of the module

Expressions:

- {{ name }} -> Binds value of name from current scope and watches for changes to name

- {{ ::name }} -> Binds value of name from current scope and doesn’t watch for change (Added in AngularJS 1.3)

Utility functions

- angular.copy - Creates a deep copy of source
- angular.extend - Copy methods and properties from one object to another
- angular.element - Wraps a raw DOM element or HTML string as a jQuery element
- angular.equals - Determines if two objects or two values are equivalent
- angular.forEach - Enumerate the content of a collection
- angular.toJson - Serializes input into a JSON-formatted string
- angular.fromJson - Deserializes a JSON string
- angular.identity - Returns its first argument
- angular.isArray - Determines if a reference is an Array
- angular.isDate - Determines if a value is a date
- angular.isDefined - Determines if a reference is defined
- angular.isElement - Determines if a reference is a DOM element
- angular.isFunction - Determines if a reference is a Function
- angular.isNumber - Determines if a reference is a Number
- angular.isObject - Determines if a reference is an Object
- angular.isString - Determines if a reference is a String
- angular.isUndefined - Determines if a reference is undefined
- angular.lowercase - Converts the specified string to lowercase
- angular.uppercase - Converts the specified string to uppercase

Ui-router:
- ui-sref A directive that binds a link (<a> tag) to a state.
- ui-sref-active A directive working alongside ui-sref to add classes to an element when the related ui-sref directive's state is active, and removing them when it is inactive.
- $state.go Convenience method for transitioning to a new state.
- $state.reload()  force reloads the current state.
- ui-view The ui-view directive tells $state where to place your templates. A view can be unnamed or named.
