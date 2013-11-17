AngularJS-Samples
=================

Angular JS Simple to Complext Examples

Good Links For Learning Angular
=============================
Angular Cheat Sheet - http://www.cheatography.com/proloser/cheat-sheets/angularjs/#comments  <br>
Free Tutorial Videos - http://egghead.io/lessons <br>
Angular Examples    - https://github.com/angular/angular.js/wiki/JsFiddle-Examples <br>
http://docs.angularjs.org/cookbook/advancedform <br>

Fantastic Series to clear all your concepts of angular - http://www.ng-newsletter.com/posts/directives.html <br>
 http://www.ng-newsletter.com/posts/beginner2expert-directives.html
 
 AngularJS Videos - http://www.angularjsdaily.com/
 
 http://www.artandlogic.com/blog/2013/05/angularjs-best-practices-ive-been-doing-it-wrong-part-3-of-3/



angular.copy
angular.element
angular.equals
angular.extend
angular.forEach
angular.fromJson
angular.identity
angular.isArray
angular.isDate
angular.isDefined
angular.isElement
angular.isFunction
angular.isNumber
angular.isObject
angular.isString
angular.isUndefined
angular.lowercase
angular.noop
angular.toJson
angular.uppercase
Companion Libra

Notes
=====

$location - Angular provides this service which  Exposes the current url in the browser <br>
            address bar, so you can watch,observe and change the URL. <br>
            e.g $location.path("/").replace() will redirect the users back to home page
            .replace() bascially delete the history part of it
            
ngResource Module - ngResource module allows to communite with REST Services.
you need to declare it as a dependency on the ngController
so e.g angular.module('Contacts',['ngResource'], also ngresource does not come as a part and parcel of angular,<br>
so need to import it    angular-resource.js. <br>
With this we get a $resource object which lets u declare services we can access on the server<br>
e.g var Contact = $resource('/api/contact');
            


