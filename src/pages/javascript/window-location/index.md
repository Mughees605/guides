---
title: Window Location
---
## Useful Links
<a href='https://developer.mozilla.org/en-US/docs/Web/API/Window/location' target='_blank' rel='nofollow'>MDN LINK</a>

## Window Location

## EXAMPLES

You can use JavaScript to control the browser. To begin with, you can get the browser to tell you its current location

## window.location.href

let url = window.location.href;

For example, if the browser is currently at https://github.com/freeCodeCamp/guides the statement above will assign the string "https://github.com/freeCodeCamp/guides" to the variable url

## window.location.hostname

You can also get pieces of this url.

For example, if the you want to get the domain name of url. You can use

let domainName = window.location.hostname;

In the example, the string "github.com" is assigned to the variable domainName. "http://", the path, and the anchor are omitted.

## window.location.pathname

If you want to get the pathname of the url. You can use

let pathname = window.location.pathname;

In the example, the string "/freeCodeCamp/guides" is assigned to the variable pathname.

## window.location.hash

let theAnchor = window.location.hash;

Since there is no anchor in the url we use above, the variable is assigned an empty string.

## window.location.assign

The statement directs the browser to the home page of freecodecamp.
window.location.assign("http://www.freecodecamp.com").

## window.location.replace

window.location.replace("http://www.freecodecamp.com")
the statement directs the browser to a new URL. But by using replace 
instead of assign, you interfere with the browser history. When you use assign, the history is
intact. The statement takes the user away from the original page, to the new page. If, after
arriving at the new page, she presses the Backspace key or clicks the browser's back button,
she goes back to the original page that she just came from. But when you use replace, the
original page doesn't make it into the history. If the user presses Backspace after being taken
to the new page, she's taken to the page that displayed before the original page since the
original page is no longer in the history. If there is no page before the original page, nothing
happens when she presses Backspace.
