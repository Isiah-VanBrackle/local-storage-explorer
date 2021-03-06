[![Build Status](https://travis-ci.org/Deliaz/local-storage-explorer.svg?branch=master)](https://travis-ci.org/Deliaz/local-storage-explorer)
[![Chrome Web Store](https://img.shields.io/chrome-web-store/stars/hglfomidogadbhelcfomenpieffpfaeb.svg)](https://chrome.google.com/webstore/detail/local-storage-explorer/hglfomidogadbhelcfomenpieffpfaeb)

## Local Storage Explorer

**Google Chrome extension for Web Developers**

Local Storage Explorer brings you better ability to explore localStorage and sessionStorage values.
It integrates with DevTools panel and can parse and beautify JSON values.

<img src="imgs/128.png" alt="Local Storage Explorer logo">

[**&raquo; Install from Chrome Web Store**](https://chrome.google.com/webstore/detail/local-storage-explorer/hglfomidogadbhelcfomenpieffpfaeb)

### Features
 * JSON parser & beautifier
 * Shows value type and length
 * Delete keys and clear storage in one click
 * Light and Dark themes
 * Adaptive design

### Screenshots
<kbd>
	<img src="screenshots/Screen1.png" alt="Screenshot 1" width="260">
</kbd>
<kbd>
	<img src="screenshots/Screen2.png" alt="Screenshot 2" width="260">
</kbd>
<kbd>
	<img src="screenshots/Screen3.png" alt="Screenshot 3" width="260">
</kbd>

### Contribute
To build extension just run:
 1. `npm install`
 2. `gulp`

It will create two folders: 
 * `build/` &ndash; contains built files
 * `dist/` &ndash; contains compressed zip-file with files from `built`

#### Todo list

* parse JWT tokens
* make i18n
* comments
* adjustable width of key list
* keyboard navigation in key list
* open by browser action?
* choose better icons
* parse timestamps
* other json-view libraries?
