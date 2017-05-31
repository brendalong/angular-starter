# Angular-Starter
Intro slides: http://slides.com/brendalong/deck#/

### Some Terms
* Dependency injection - how components get hold of their dependencies. Angular is in charge of creating components, resolving dependencies and providing them to other components as __requested__.

* Components (services, directive, filters, animations) are defined by an injectable factory method or constructor function. These can be injected with service and values a dependencies.
* Controllers (constructor function) can be injected with service and value components as dependcies.
* Run accepts a function which can be injected with service, value and constant 
* Config accepts a function wich can be injected with provider and constant components.


NO (MANUAL) DOM MANIPULATION
1. DIRECTIVES - AngularJS directives are extended HTML attributes with the prefix ng-.
    * The `ng-app` directive initializes an AngularJS application.
    * The `ng-init` directive initializes application data.
    * The `ng-model` directive binds the value of HTML controls (input, select, textarea) to application data.
1. CONTROLLERS - control the data and are regular JS objects.
1. $scope - binding part between the HTML (view) and the JavaScript (controller).
1. SERVICES - a service is a function, or object, that is available for, and limited to, your AngularJS application. For example: `$location` provides the location of the page 
1. FACTORIES - get the data
1. PROVIDERS
1. FILTERS
1. ROUTING - navigate to different pages in an application, yet also as a SPA.
    * `ngRoute` and use of `ng-view`

### Check it out
* `index.html` - the world's most simple app.
* `index2.html` - simple controller with `ng-repeat`
* Chrome Extension - ng-inspector for Angular