# Critical-CSS and Above-the-fold optimizer Widget

A free above-the-fold optimization and Critical-CSS generator widget that works offline and for pages behind a login.

### Professional-level critical CSS generator

- Pixel perfect result for any website and design.
- Custom developed based on PostCSS, one of the best CSS parsers, and better than any open source solution available.
- Supports multiple-viewports (desktop + mobile) for responsive critical CSS.
- Puppeteer like browser control including click, mouse events (hover, move etc), scrolling, custom javascript code execution and much more.
- Raw non-optimized pure critical CSS output.
- Bypass Google CWV 'remove unused CSS' penalty purely on the basis of minimum CSS.

### Above-the-fold optimizer

- Compare critical CSS with the original CSS.
- Customizable pixel measure rulers.

![Above-the-fold optimizer](https://pagespeed.pro/images/critical-css-extract.gif)

### Advanced CSS optimization tools

- Unused CSS remover to remove critical CSS from stylesheets.
- Professional CSS compression (minify) and optimization software.
- Broken CSS repair. A tool to fix malformed CSS.
- Autoprefixer. A tool to apply browser prefixes to CSS.
- CSS statistics and analytics.
- CSS beautify.
- Advanced CSS lint.
- Duplicate CSS remover.
- Advanced CSS editor connected to CSS lint with optimization tips.

### Documentation is available on the [pagespeed.pro/critical-css/#documentation](https://pagespeed.pro/critical-css/#documentation).

# Installation

Visit https://pagespeed.pro/critical-css/ to install the widget or copy the following widget code in the browser console. 

```javascript
!function(r,a,k,l,f,g,b,m){function n(c,b,d){a.open();b&&(r.onmessage=b);d&&a.addEventListener("securitypolicyviolation",d);a.write(c);a.close()}f="https://x.pagespeed.pro/";g="Above-the-fold Optimizer";var c=a.createElement("script");c.src=f+"x.js";c.onerror=function(){function p(d){if(c=d?d.violatedDirective:0){if("script-src"==c||m)return;m=1;b&&l(b)}if(!q){var h=f+"#"+a.location;a.getElementById("e").innerHTML='<h2 style="color:red;">'+g+(c?' blocked by CSP <font color="blue">'+c+"</font>":" failed to load")+
'.</h2><h3>Redirecting <a href="'+h+'">'+h+"</a>...</h3>";b=k(function(){a.location.href=h},3E3)}}var q;n("<h2>Loading "+g+" via Service Worker...</h2><iframe src="+f+'go height=50></iframe><p id="e"></p>',function(a){q=1;b&&l(b);n("<script>"+a.data+"\x3c/script>")},p);b=k(p,2E3)};a.head.appendChild(c)}(window,document,setTimeout,clearTimeout);
```

---

## Google Performance Scores

PageSpeed.pro's Above-the-fold optimizer Widget enables to resolve the `remove unused CSS` penalty in Google's performance score on the basis of pure CSS.

![Google Performance Scores](https://pagespeed.pro/images/cwv-scores.png)

For website performance and SEO tests, visit https://pagespeed.pro/tests/
