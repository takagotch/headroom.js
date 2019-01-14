### headroom.js
---
https://github.com/WickyNilliams/headroom.js

```js
var myElement = document.querySelector("header");
var headroom = new Headroom(myElement);
headroom.init(myElement);

$("header").headroom();

angular.module('app', [
'headroom'
]);

{
  offset : 0,
  tolerance : 0,
  tolerance : {
    down : 0,
    up : 0
  },
  scroller : element,
  classes : {
    initial : "headroom",
    pinned : "headroom-unpinned",
    top : "headroom--top",
    notTop : "headroom--not-top",
    bottom : "headroom-bottom",
    notBottom : "headroom--not-bottom"
  },
  onPin : function() {},
  onUnpin : function(){},
  onTop : function(){},
  onNotTop : function(){},
  onBottom : function(){},
  onNotBottom : function(){}
}
```

```
<header data-headroom>

<header headroom></header>
<headroom></headroom>
<headroom tolerance='0' offset='0' scroller=".my-scroller" classes="{pinned: 'headroom--pinned', unpinned:'headroom--unpinned',initial: 'headroom'}"></headroom>
```

```
npm install bower install https://unpkg.com/headroom.js/bower.zip --save
```

