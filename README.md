BITADDRESSGEN
=============

JavaScript Client-Side Bitcoin Wallet Generator

Now Bitcoin addresses and their corresponding private key can be conveniently 
generated in a web browser.

The BITADDRESSGEN project provides an all-in-one HTML document with embedded
JavaScript/Css/Images. The JavaScript is readable not minified and contains no
XMLHttpRequest's (no AJAX). The benefit of this technique is you can load the 
JavaScript locally and trust that the JavaScript did not change after being 
loaded.


END USER NOTES:
---------------

 1) For Bulk Wallet I recommended using Google Chrome, it's the fastest.

 2) Requires IE9+, Firefox, Chrome or sufficient JavaScript support.

 3) Mobile Safari only works with iPhone4 or newer devices.
    Older devices timeout while executing JavaScript.

 4) DO NOT use Opera Mini it renders JavaScript output server side, therefore
    they might record the private key you generated.

 5) BIP38 most likely will not work on mobile devices due to hardware limitations.


 DEVELOPER NOTES:
-----------------

1) $ npm install

2) $ grunt

