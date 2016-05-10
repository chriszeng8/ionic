$ ionic start myapp blank
$ cd myapp
$ ionic serve


Note that ionic Lab can also create a myapp from GUI.
Clicking the ```Serve``` button is the Ionic lab is the same as ```$ ionic serve``` from command prompt.


Edit the follwoign two files to start with:
1. ```index.html``` under ```www``` folder.
2. ```app.js``` under ```www/js``` folder.

Ionic Lab is actually a customized version of chrome. You can tell by goign to ```View->Toggle DevTools``` or ```alt+Command+I``` for shortcut key, in fact it is the same shortcut key as in Chrome browser.

Basic Skeleton 
* ionic.css & style.css
* ionic.bundle.js (Ionic & AngularJS, need it at all time)
* cordova.js (what makes ionic looks like a native iOS/Android app, needed when running on mobile device, not needed for Chrome browser Preview)
* app.js (angular module + cordova keyboard plugin, control position of keyboard focused area) 
* ng-app: autobootstrap AngularJS app
* Ionic apps are written in AngularJS
* Directives: ion-pane, ion-header-bar, ion-content

First, Install ionic Snippet by going to "install package" (Command+Control+P), type ```package control Install package```, then search for ionic framework snippet and install it.

We can now use the ion snippet to quickly ionic elements with the 
e.g.,
```
ion-list>ion-item*3
```
will easily populate the following ion item list:
```
<ion-list>
	<ion-item></ion-item>
	<ion-item></ion-item>
	<ion-item></ion-item>
</ion-list>
```

Ionic Creator is a drag and drop app outline creator, which allows us to drag a element into the view.

[Ionic Marketplace](https://market.ionic.io/) is a store for purchasing templates.

