# Responsive Navigation Menu
Great and easy to use responsive and multi-level navigation menu

[Responsive navigation menu](https://webgadgets.net/plugins/responsive-navigation-menu) plugin helps you to create menu which transforms on defined resolution to mobile menu.

## Quick start

### 1. Load jQuery and include Responsive Navigation Menu plugin files 
```html
<link href="dist/responsive-nav.min.css" rel="stylesheet" type="text/css"/>
<script src="jquery.js" type="text/javascript"></script>
<script src="dist/responsive-nav.min.js" type="text/javascript"></script>
```

 ### 2. Set up your HTML 
```html
<nav id="nav-menu">
    <div class="label-menu">menu</div>
    <div>
        <ul>
            <li class="dropdown">
                <a href=""><span>list item First Level 1</span></a>
                <div>
                    <ul>
                        <li><a href="#"><span>list item Second Level 1.1</span></a></li>
                        <li><a href="#"><span>list item Second Level 1.2</span></a></li>
                        <li><a href="#"><span>list item Second Level 1.3</span></a></li>
                    </ul>
                </div>
            </li>
            <li><a href="#"><span>list item First Level 2 </span></a></li>
            <li><a href="#"><span>list item First Level 3 </span></a></li>
        </ul>
    </div>
</nav>
```

### 3. Call the plugin 
```js
$(document).ready(function() {
    $("#nav-menu").responsiveNav();
});
```
## Documentation
For the whole functionality of Responsive Navigation Menu, see [documentation](https://webgadgets.net/plugins/responsive-navigation-menu/doc).
