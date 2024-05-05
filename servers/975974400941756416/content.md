This wiki is for a test server, the assets seen are from THCoTD (TO-DO: link to THCoTD wiki when made).

# Section
This is a section, headers will show in the table of contents. \
Test of custom image implementation: 

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco <wiki-image file="terry-davis-wobble.gif" placement="left" size="250">Terry A. Davis got them moves!</wiki-image> laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Code block of example image tests:
```
This aligns the image to the left side of the paragraph:
<wiki-image file="terry-davis-wobble.gif" placement="left">This is a caption</wiki-image>
text text text
[image] text
text text text

This aligns the image to the right side of the paragraph:
<wiki-image file="terry-davis-wobble.gif" placement="right">This is a caption</wiki-image>
Ex.
text text text
text   [image]
text text text

This breaks the text and aligns it in the middle:
<wiki-image file="terry-davis-wobble.gif" placement="break">This is a caption</wiki-image>
Ex.
text text text
    [image]
text text text
```
<br/>
Channel test:<br/>
<wiki-channel>test-channel</wiki-channel>
<br/>
backslash newline test\n\n 
User test:<br/>
<wiki-user>user</wiki-channel>