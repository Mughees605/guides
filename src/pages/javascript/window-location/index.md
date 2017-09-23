---
title: Window Location
---
## Window Location

You can use JavaScript to control the browser. To begin with, you can get the browser to tell you its current location

var url = window.location.href;

For example, if the browser is currently at https://github.com/freeCodeCamp/guides the statement above will assign the string "https://github.com/freeCodeCamp/guides" to the variable url

You can also get pieces of this url.

For example, if the you want to get the domain name of url. You can use

var domainName = window.location.hostname;

In the example, the string "github.com" is assigned to the variable domainName. "http://", the path, and the anchor are omitted.

If you want to get the pathname of the url. You can use

var pathname = window.location.pathname;

In the example, the string "/freeCodeCamp/guides" is assigned to the variable pathname
