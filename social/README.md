Social Bookmarklets
===================

Drag the links below into your bookmarks bar

"Pint it", from Pinterest
-------------------------

``` js
javascript:void((function(d){var e=d.createElement('script');e.setAttribute('type','text/javascript');e.setAttribute('charset','UTF-8');e.setAttribute('src','//assets.pinterest.com/js/pinmarklet.js?r='+Math.random()*99999999);d.body.appendChild(e)})(document));
```

Source: http://pinterest.com


"Add to Delicious", from Delicious
----------------------------------

``` js
javascript:(function(e,t){var n=e.document;setTimeout(function(){function a(e){if(e.data==="destroy_bookmarklet"){var r=n.getElementById(t);if(r){n.body.removeChild(r);r=null}}}var t="DELI_bookmarklet_iframe",r=n.getElementById(t);if(r){return}var i="https://delicious.com/save?",s=n.createElement("iframe");s.id=t;s.src=i+"url="+encodeURIComponent(e.location.href)+"&title="+encodeURIComponent(n.title)+"&note="+encodeURIComponent(""+(e.getSelection?e.getSelection():n.getSelection?n.getSelection():n.selection.createRange().text))+"&v=1.1";s.style.position="fixed";s.style.top="0";s.style.left="0";s.style.height="100%25";s.style.width="100%25";s.style.zIndex="16777270";s.style.border="none";s.style.visibility="hidden";s.onload=function(){this.style.visibility="visible"};n.body.appendChild(s);var o=e.addEventListener?"addEventListener":"attachEvent";var u=o=="attachEvent"?"onmessage":"message";e[o](u,a,false)},1)})(window)
```

Source: https://delicious.com/tools
