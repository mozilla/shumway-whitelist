# Shumway whitelist

Firefox uses the Shumway whitelist to determine which Flash content (swf files) should be played with [Mozilla's Shumway extension](http://www.areweflashyet.com/) instead of Adobe's Flash Player plugin.

mozpub-shumway.txt is a list of shavar suffix/prefix expressions as documented in Google's [Safe Browsing API Developer's Guide](https://developers.google.com/safe-browsing/developers_guide_v2#ListContents) (v2.2). Lines proceeded by a `#` character are comments. The whitelist is imported into Mozilla's shavar service and then distributed to Firefox clients (as shavar table `mozpub-shumway-digest256`).
