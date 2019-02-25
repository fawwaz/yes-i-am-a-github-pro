# Chrome Extension Boilerplate for Simple Content Scripts
[Developer Documentation for Content Scripts](https://developer.chrome.com/extensions/content_scripts)

## Instructions
  - Download this repo into a folder.
  - Launch the Chrome browser.
  - Navigate to [chrome://extensions/](chrome://extensions/).
  - Click the "Load unpacked extension..." button on the top left of the screen.
  - Choose the folder you just created and click OK.
  - Whenever you make a change to the extension, go back to this page and click the "reload" button on this extension.
  - (optionally) You can add [Extensions Reloader](https://chrome.google.com/webstore/detail/extensions-reloader/fimgfedafeadlieiabdeeaodndnlbhid?hl=en) to make development faster

## Important Files
### manifest.json
The manifest.json file describes all the specifics of your chrome extension.

### code/js.js
The javascript injected into the page.

### code/css.css
The css injected into the page.

### resources/jquery.min.js
Allows you to use the simple jQuery library we all know and love.

built by [@iamnickvolpe](http://twitter.com/iamnickvolpe)