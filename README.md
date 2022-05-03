# praqticalfox
A two-line, although very compact, Firefox CSS theme, with editable options for Windows, Mac, and Elementary OS.

It probably has glitches idk

<img src="preview1.png" width=500px> <img src="preview2.png" width=500px>

<img src="preview 3.png" width=600px>

It also has support for themes downloaded from the Firefox store



# How to install:
1) Download my theme by clicking on the green button with the text "Code" at the top of this page
2) Open Firefox, and enter "about:config" in the URL bar
3) In about:config, search for "ui.prefersReducedMotion" - it's likely that nothing will show up, so create that key as a number, and set it to 1
4) Also set "toolkit.legacyUserProfileCustomizations.stylesheets" to 1
5) Close about:config, and open about:profiles
6) There will be 4 buttons, all labeled "Open Directory" - click on the first one
7) In the folder it opened, create a new folder called "chrome"
8) Drag and drop my "userChrome.css" file that you downloaded, into the "chrome" folder you just created
9) Restart Firefox :)

Here's how my "customize Firefox" page is set up, I recommend you set it up the same way
<img src="layout.png">

If you're on Mac or Elementary OS, I'd recommend poking around the userChrome.css file, there's options at the bottom of the file to move the window buttons to the left/eOS style
