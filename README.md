# generator-lateralus

A [Yeoman](http://yeoman.io) generator for [Lateralus](https://github.com/Jellyvision/lateralus) apps.

To install generator-lateralus:

````
npm install -g generator-lateralus
````

To create and install a new Lateralus app:

````
mkdir my-new-project && cd $_
yo lateralus
````

To create a new component:

````
yo lateralus:component [component-name]
````

Components must be `named-like-this`.

__Note__: Components will not be automatically wired up as [RequireJS packages](http://requirejs.org/docs/api.html#packages) after being created.  This must be done manually in your `app/scripts/main.js` file.
