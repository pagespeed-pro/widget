# 📐 Style.Tools Browser Widget

A fast browser widget for 1-click access to CSS code research and optimization tools with offline and localhost support. 

### Documentation is available on the [Wiki](https://github.com/style-tools/browser-widget/wiki).

[CMS plugins](https://github.com/style-tools) are available for WordPress and many others. 

## Usage 

Visit https://style.tools/ to install the widget or copy the following widget code in the browser console. 

```javascript
!function(r,a,k,l,f,g,b,m){function n(c,b,d){a.open();b&&(r.onmessage=b);d&&a.addEventListener("securitypolicyviolation",d);a.write(c);a.close()}f="https://style.tools/";g="Style.Tools";var c=a.createElement("script");c.src=f+"x.js";c.onerror=function(){function p(d){if(c=d?d.violatedDirective:0){if("script-src"==c||m)return;m=1;b&&l(b)}if(!q){var h=f+"#"+a.location;a.getElementById("e").innerHTML='<h2 style="color:red;">'+g+(c?' blocked by CSP <font color="blue">'+c+"</font>":" failed to load")+
'.</h2><h3>Redirecting <a href="'+h+'">'+h+"</a>...</h3>";b=k(function(){a.location.href=h},3E3)}}var q;n("<h2>Loading "+g+" via Service Worker...</h2><iframe src="+f+'go height=50></iframe><p id="e"></p>',function(a){q=1;b&&l(b);n("<script>"+a.data+"\x3c/script>")},p);b=k(p,2E3)};a.head.appendChild(c)}(window,document,setTimeout,clearTimeout);
```

A good website to test is https://www.w3schools.com/

Style.Tools is like Dev Tools for CSS optimization. It looks similar and the startup time is instant.

##### Bookmark
![image](https://user-images.githubusercontent.com/8843669/50855172-6d7e0980-1387-11e9-89dc-6535dd846fff.png)

![image](https://user-images.githubusercontent.com/8843669/50855020-ffd1dd80-1386-11e9-9116-1d26258cba8e.png)

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

The `Original View Settings` enables to configure a CORS proxy and to include cookies in the request to allow access to pages behind a login.

#### Google Webmaster Tools UI

![Google Webmaster Tools CSS](https://github.com/style-tools/browser-widget/blob/master/images/editor-signed-in.png)

#### Netflix

![CSS Editor](https://github.com/style-tools/browser-widget/blob/master/images/css-editor.png)

#### Amazon AWS UI

![Amazon AWS UI](https://github.com/style-tools/browser-widget/blob/master/images/aws-abtf.png)

Style.Tools provides access to the full CSS of the UI, including all async injected `<style>` and `<link>` elements. With a few clicks and in less than a few seconds you can get a good insight in how a complex UI is made. Over time, this ability enables to learn a lot about professional CSS design.

## Critical CSS generator

A CSS management tab provides easy access to all stylesheets on a page with options to download stylesheets, concatenate (merge) and an option to download multiple stylesheets in a ZIP package.

The Critical CSS generator was custom made and is able to provide a perfect result. It was inspired by [Penthouse.js](https://github.com/pocketjoso/penthouse) and improved on many aspects including the use of PostCSS as a CSS parser. As a browser widget it has access to async injected stylesheets of the choice of the editor.

![Critical CSS Generator](https://github.com/style-tools/browser-widget/blob/master/images/css-settings.png)

## CSS Statistics

Comprehensive CSS statistics provide a deep analysis of the CSS respresented in numbers and made visual with a color palette.

![Above The Fold optimization](https://github.com/style-tools/browser-widget/blob/master/images/css-stats.png)
