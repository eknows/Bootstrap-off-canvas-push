#Bootstrap push style off canvas menu

## Description
Bootstrap navigation hack for push style off canvas menu.

1. Only works with navbar-static-top
2. jQuery is required
3. jQuery mobile is required for touch events, build it here: http://jquerymobile.com/download-builder/
4. Bootstrap ist required
5. Hack your Bootstrap navigation:

Add directly after the body tag
```<div class="overlay"></div>```

Change data-toggle to offcanvas
```<button type="button" class="navbar-toggle collapsed" data-toggle="offcanvas" aria-controls="navbar">```

Add class navbar-static-top
```<nav class="navbar navbar-inverse navbar-static-top">```

Add class pull-left to navbar Button
```<button type="button" class="navbar-toggle collapsed pull-left" data-toggle="offcanvas" aria-controls="navbar">```

Add class sidebar-offcanvas
```<div id="navbar" class="collapse navbar-collapse sidebar-offcanvas">```

Add class row-offcanvas and row-offcanvas-left inside the container
```<div class="row-offcanvas row-offcanvas-left">```

## Demo Time
http://jsfiddle.net/0Lw4mbzg/2/
