# ng-img-preload
AngularJS Directive for preloading and detecting background image load on elements.
Using this method you are able to detect when the background image is loaded and therefore able to add in loaders and entrance animations to your elements

# Usage

1.  Add 'ngBackgroundPreload' to your app dependencies
2.  Use the directive in a template on the element you want to load the background on:
```html
 <div ng-background-preload image-url="/images/your-image.jpg" class-on-load="loaded"></div>

```