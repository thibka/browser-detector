# browser-detector

## Install
```bash
npm i @thibka/browser-detector
```

## Usage
```javascript
import BrowserDetector from '@thibka/browser-detector';

var supportES6 = BrowserDetector.supportES6(); // true / false
var isChrome = BrowserDetector.isChrome(); // true / false
var isIE11 = BrowserDetector.isIE11(); // true / false
var isFirefox = BrowserDetector.isFirefox(); // true / false
var isSafari = BrowserDetector.isSafari(); // true / false
var isMobile = BrowserDetector.isMobile(); // true / false
var isMobileOrTablet = BrowserDetector.isMobileOrTablet(); // true / false
```