ngDrop
======

Angularjs advanced dropdown. Pure DOM.


Description
-----------
UI dropdown similar in behaviour to HTML's select tag with the following enhancements:
- Search field to filter matching results. 
- Grouping of items.

How to use?
-----------
Include the css:
```html
<link rel="stylesheet" href="ng-drop.css"></link>
```

and js:

```html
<script src="ng-drop.js"></script>
```

Finally, include the module in your main angular app:


```js
angular.module('yourApp', ['ngDrop']);
```

In the html DOM, for example:
```html
<dropdown dropdown-model="selected" dropdown-placeholder="-- Select --">
	<dropdown-group name="group 1">
		<dropdown-item>Item a1</dropdown-item>
		<dropdown-item>Item a2</dropdown-item>
	</dropdown-group>
	
	<dropdown-group name="group 2">
		<dropdown-item>Item b1</dropdown-item>
		<dropdown-item>Item b2</dropdown-item>
	</dropdown-group>
	
	<dropdown-group name="group 3">
		<dropdown-item>Item c1</dropdown-item>
		<dropdown-item>Item c2</dropdown-item>
	</dropdown-group>
</dropdown>
```

In case no group is needed, use anonymous group:
```html
<dropdown dropdown-model="selected" dropdown-placeholder="-- Select --">
	<dropdown-group>
		<dropdown-item>Item 1</dropdown-item>
		<dropdown-item>Item 2</dropdown-item>
		<dropdown-item>Item 3</dropdown-item>
		<dropdown-item>Item 4</dropdown-item>
	</dropdown-group>
</dropdown>
```

Try it!
-------

A live demo [plunker](http://plnkr.co/edit/E0uuy7LoLtOFBOGCEJ4E?p=info).
