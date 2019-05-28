# Style.Tools FEO Widget

A free Frontend Optimization (FEO) widget that works offline and for pages behind a login.

- extract critical CSS
- CSS editor
- CSS beautify
- CSS minify / optimization
- repair broken CSS
- remove unused CSS
- remove duplicate CSS
- PostCSS plugins: autoprefixer
- CSS lint
- CSS analysis

### Documentation is available on the [docs.style.tools](https://docs.style.tools/).

# Installation

Visit https://style.tools/ to install the widget or copy the following widget code in the browser console. 

```javascript
!function(r,a,k,l,f,g,b,m){function n(c,b,d){a.open();b&&(r.onmessage=b);d&&a.addEventListener("securitypolicyviolation",d);a.write(c);a.close()}f="https://style.tools/";g="Style.Tools";var c=a.createElement("script");c.src=f+"x.js";c.onerror=function(){function p(d){if(c=d?d.violatedDirective:0){if("script-src"==c||m)return;m=1;b&&l(b)}if(!q){var h=f+"#"+a.location;a.getElementById("e").innerHTML='<h2 style="color:red;">'+g+(c?' blocked by CSP <font color="blue">'+c+"</font>":" failed to load")+
'.</h2><h3>Redirecting <a href="'+h+'">'+h+"</a>...</h3>";b=k(function(){a.location.href=h},3E3)}}var q;n("<h2>Loading "+g+" via Service Worker...</h2><iframe src="+f+'go height=50></iframe><p id="e"></p>',function(a){q=1;b&&l(b);n("<script>"+a.data+"\x3c/script>")},p);b=k(p,2E3)};a.head.appendChild(c)}(window,document,setTimeout,clearTimeout);
```

---

## Google Performance Scores

Style.Tools FEO Widget enables to resolve the `remove unused CSS` penalty in Google's performance score on the basis of pure CSS.

![Google Performance Scores](https://style.tools/google-measure-scores.png)

For website and SEO tests, visit https://pagespeed.pro/
