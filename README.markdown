**THIS PROJECT IS NO LONGER MAINTAINED.  IT MOSTLY WORKS, I have created this prject as Part of my online blog Tutorails.BUT IF YOU RUN INTO ISSUES, CHECK OUT THE FORKS, PLEASE.  OR FIX IT YOURSELF.  CHEERS!**

* * *

# jquery-base64

Rather simple jQuery'fication of
[Nick Galbreath's base64 string encoder](http://stringencoders.googlecode.com/svn-history/r210/trunk/javascript/base64.js).

I didn't like having a global `base64` variable around, that's all.


## Usage

* `$.base64.encode( "this is a test" )` returns `"dGhpcyBpcyBhIHRlc3Q="`
* `$.base64.decode( "dGhpcyBpcyBhIHRlc3Q=" )` returns `"this is a test"`


## Known issues

JSLint is complaining about the "unexpected use of '<<'/'|'".  No idea, suggestions welcome.


## Developers

Original code by [Nick Galbreath](http://stringencoders.googlecode.com/svn-history/r210/trunk/javascript/base64.js).
Port by [Carlo Zottmann](http://github.com/carlo).
Futher extended by [Sajjad Ashraf] (https://github.com/sajjad037).
for more detail please read [Oline Base64 Encode and Decode] (http://visualstudiolearn.blogspot.com/2016/07/oline-base64-encode-and-decode.html).
another example by [gabrieleromanato ] (https://jsfiddle.net/gabrieleromanato/qaght/).


## License

MIT license, just like [the original](http://stringencoders.googlecode.com/svn-history/r210/trunk/javascript/base64.js).
