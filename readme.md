# FST MMENU 

Simple and light wieght javascript over-canvas mobile menu for website and web application.

## Installation
```bash
npm install fst-mobile-menu
```

## Howe to use
initialize fstMmenu ALLWAYS in (document) ready statement
```javascript
$(document).ready(function(){
   $('#mobile-menu').fstMmenu();
})
```


> **NOTE**   Create button element with **fst-menu-toggler** class name to show/hide menu


## Configuration Parameters
When you call "fstMmenu" and can pass some parameters to custom visual aspects.

```javascript
$("mobile-menu").fstMmenu({
   position: "right"  //change the menu positon [right, left, top, bottom],
   width: 350 //change the width for [left, right] position. width value set to height on [top, bottom] positon.
   menuToggler: 'fst-menu-toggler', // mobile menu icon selector to toggle the menu ( Please provide the class name without dot :) )
   closeIcon: 'SVG ICON' // change the close icon (can put any string),
   arrowDownIcon: 'SCG ICON' //change the arrow down for toggle the sub menu (can put any string),
   overlay: true //show and hide the overlay
})
```

**Note**  
Above Sample object are default parameters for that closeIcon and arrowDownIcon we used the svg icons

>[Tabindex loop Tutorial](http://bluegalaxy.info/codewalk/2018/08/04/javascript-how-to-create-looping-tabindex-cycle/)
## Coming Feature 
- Off canvas layout menu