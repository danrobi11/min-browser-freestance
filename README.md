# min-freestance
 Redirector script from mainstream websites to their privacy-supporting mirrors for the [min](https://github.com/minbrowser/min) browser
 
 # Usage
 Create a ```userscript.js``` file following [this guide](https://github.com/minbrowser/min/wiki/userscripts) (called whatever you'd like) for your script.

Example: To automatically redirect ```youtube.com``` to ```invidious.snopyta.org``` add this in your ```userscript.js``` file.

```
// ==UserScript==
// @name Redirect to invidious
// @match https*://youtube.com
// @match https*://www.youtube.com
// @run-at document-start
// ==/UserScript==

window.location.hostname = 'invidious.snopyta.org'
```

You need to create a ```userscript.js``` for every websites you'd like to be redirected to.

Credit: [PalmerAL](https://github.com/PalmerAL)
