# Style.Tools Browser Widget

A fast browser widget for 1-click access to CSS research and optimization tools with offline and localhost support.

### Documentation is available in the [Wiki](https://github.com/style-tools/browser-widget/wiki)

## Usage 

Visit https://style.tools/ to install the widget or copy the following widget code in the browser console.

```javascript
!function(r,a,k,l,f,g,b,m){function n(c,b,d){a.open();b&&(r.onmessage=b);d&&a.addEventListener("securitypolicyviolation",d);a.write(c);a.close()}f="https://style.tools/";g="Style.Tools";var c=a.createElement("script");c.src=f+"x.js";c.onerror=function(){function p(d){if(c=d?d.violatedDirective:0){if("script-src"==c||m)return;m=1;b&&l(b)}if(!q){var h=f+"#"+a.location;a.getElementById("e").innerHTML='<h2 style="color:red;">'+g+(c?' blocked by CSP <font color="blue">'+c+"</font>":" failed to load")+
'.</h2><h3>Redirecting <a href="'+h+'">'+h+"</a>...</h3>";b=k(function(){a.location.href=h},3E3)}}var q;n("<h2>Loading "+g+" via Service Worker...</h2><iframe src="+f+'go height=50></iframe><p id="e"></p>',function(a){q=1;b&&l(b);n("<script>"+a.data+"\x3c/script>")},p);b=k(p,2E3)};a.head.appendChild(c)}(window,document,setTimeout,clearTimeout);
```

The Style.Tools editor works best when used from the bookmarks bar. Fetch requests will then be local without the need for a [CORS proxy](https://gist.github.com/jimmywarting/ac1be6ea0297c16c477e17f8fbe51347).

Style.Tools is like Dev Tools for CSS optimization. It looks similar and the startup time is instant.

Style.Tools provides access to many tools for CSS code research and optimization. 

- [PostCSS](https://github.com/postcss/) plugins
- [clean-css](https://github.com/jakubpawlowicz/clean-css)
- Code structure optimization tools
- Critical CSS generators, two unique solutions:
	1) a simple browser widget (inspired by [this snippet](https://gist.github.com/PaulKinlan/6284142))
	2) professional quality Critical CSS based on PostCSS and inspired by [Penthouse.js](https://github.com/pocketjoso/penthouse).
- Unused CSS remover (high quality result based on PostCSS)
- Repair broken CSS (find & fix syntax errors)
- [Autoprefixer](https://github.com/postcss/autoprefixer)
- [CSS Analytics](https://github.com/cssstats/cssstats)
- [CSS LINT](https://github.com/CSSLint/csslint)
- A live CSS editor with over 50 themes
- Above the fold optimization tools
- Concatenation
- Download individual stylesheets or ZIP-package
- A measurement grid with many unit formats (cm, decimal, pt, px etc)
- Capture of async injected stylesheets.

The editor is part free and part premium. The free version provides CSS beautify, minify and a simple critical CSS extractor. The premium version provides access to more professional optimization tools. 

## Above The Fold optimization

The editor provides a split view for critical CSS and above the fold optimization.

![Above The Fold optimization](https://github.com/style-tools/browser-widget/blob/master/images/above-the-fold.png)

## CSS editor with themes

If you ever wondered how popular sites like Netflix or Google AdWords UI are made, Style.Tools enables to get an indepth insight in just a few seconds. The `beautify` feature can structure the CSS in a second enabling to get a good perspective of how the design is made.

![CSS Editor](https://github.com/style-tools/browser-widget/blob/master/images/css-editor.png)

The `Original View Settings` enables to configure a CORS proxy and to include cookies in the request to allow access to pages behind a login.

![Google Webmaster Tools CSS](https://github.com/style-tools/browser-widget/blob/master/images/editor-signed-in.png)

## Critical CSS generator

A CSS management tab provides easy access to all stylesheets on a page with options to download stylesheets, concatenate (merge) and an option to download multiple stylesheets in a ZIP package.

The Critical CSS generator was custom made and is able to provide a perfect result. It was inspired by [Penthouse.js](https://github.com/pocketjoso/penthouse) and improved on many aspects including the use of PostCSS as a CSS parser. As a browser widget it has access to async injected stylesheets of the choice of the editor.

![Critical CSS Generator](https://github.com/style-tools/browser-widget/blob/master/images/css-settings.png)

## CSS Statistics

Comprehensive CSS statistics provide a deep analysis of the CSS respresented in numbers and made visual with a color palette.

![Above The Fold optimization](https://github.com/style-tools/browser-widget/blob/master/images/css-stats.png)