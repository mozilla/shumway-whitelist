# Shumway whitelist

Firefox uses the Shumway whitelist to determine which Flash content (swf files) should be played with the Shumway extension instead of Adobe's Flash Player. The people.mozilla.org server is whitelisted to verify that Firefox is correctly processing the whitelist to play (Mozilla-controlled) Flash content using Shumway.

whitelist.txt is a list of shavar suffix/prefix expressions as documented in Google's [Safe Browsing API Developer's Guide](https://developers.google.com/safe-browsing/developers_guide_v2#ListContents) (v2.2). Lines proceeded by a `#` character are comments. The whitelist is imported into Mozilla's shavar service and then distributed to Firefox clients.
