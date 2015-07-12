# [Load Awesome](http://github.danielcardoso.net/load-awesome/)

### An awesome collection of — Pure CSS — Loaders and Spinners

A full suite of **53 animations** for websites,
created and maintained by [Daniel Cardoso](http://www.danielcardoso.net).

![Bower version](https://img.shields.io/bower/v/load-awesome.svg?style=flat-square)
![Issues](https://img.shields.io/github/issues/danielcardoso/load-awesome.svg?style=flat-square)
![License](https://img.shields.io/github/license/danielcardoso/load-awesome.svg?style=flat-square)
[![devDependency Status](https://img.shields.io/david/dev/danielcardoso/load-awesome.svg?style=flat-square)](https://david-dm.org/danielcardoso/load-awesome#info=devDependencies)


## Table of contents
- [Browser Support](#browser-support)
- [Quick start](#quick-start)
- [Usage](#usage)
- [Customising](#customising)
- [Versioning](#versioning)
- [Creator](#creator)
- [License](#license)


## Browser Support
![Chrome](https://raw.github.com/alrra/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/firefox/firefox_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/opera/opera_48x48.png)
--- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | 10+ ✔ | Latest ✔ | Latest ✔ |


## Quick start
Several quick start options are available:
- [Download the latest release](https://github.com/danielcardoso/load-awesome/releases/latest)
- Clone the repo: `git clone https://github.com/danielcardoso/load-awesome.git`
- Install with [Bower](http://bower.io): `bower install load-awesome`


## Usage
#### Standard
- Include specific css file (e.g. `ball-atom.css`)
- Create an element and add the animation class (e.g. `<div class="la-ball-atom"></div>`)
- Insert the appropriate number of childrens `<div>`s into the previous element


## Customising
#### Changing all colors
Add styles to the main:
``` css
.la-ball-atom {
    color: #79bbb5;
}
```



#### Changing color of specific elements
Add styles to the correct child `div` elements:
``` css
.la-ball-atom > div:nth-child(1) {
    color: #f4696b;
}
.la-ball-atom > div:nth-child(2) {
    color: #87c4a3;
}
.la-ball-atom > div:nth-child(3) {
    color: #fec54f;
}
```


## Versioning
Load Awesome will be maintained under the Semantic Versioning guidelines.
Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

For more information on SemVer, please visit http://semver.org.


## Creator
#### [Daniel Cardoso](http://www.danielcardoso.net)
- [@Twitter](https://twitter.com/DanielCardoso)
- [@GitHub](https://github.com/DanielCardoso)


## License
#### The MIT License (MIT)
Copyright (c) 2015 DanielCardoso.net
