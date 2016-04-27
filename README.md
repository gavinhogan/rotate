# rotate
Simple Rotation Script. Everything you need is in the index.html file

# About
This script takes slightly different approach to most rotation or carousel
scripts. Instead of swapping out the url in a single iframe, this script
adds an iframe for each url being displayed and then toggles the visibility
of the iframes. The primary benefit of this is that the browser will not
attempt to reload the page, which causes a white flash between screens. The
downside if that fresh content will NOT automatically appear. The use of
a meta refresh tag in the page head ensure the content is reloaded periodically


# Try it
https://gavinhogan.github.io/rotate
