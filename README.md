# angular-image-popup

AngularJS directive that show popup with full-sized image on hover.

## Usage

Install with bower:

```bash
bower install --save angular-image-popup
```

Add as a dependency in your Angular app:

```javascript
var app = angular.module('app', ['angularImagePopup']);
```

Use directive:

```html
<img ng-src="{{unreliableSrc}}" angular-image-popup>
```