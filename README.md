# angularimagepopup

AngularJS directive that show popup with full-sized image on hover.

## Usage

Install with bower:

```bash
bower install --save angularimagepopup
```

Add as a dependency in your Angular app:

```javascript
var app = angular.module('app', ['angularImagePopup']);
```

Use directive:

```html
<img ng-src="{{unreliableSrc}}" angularimagepopup>
```