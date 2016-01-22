# StayPuft-Dark
A fork of [StayPuft](https://github.com/dlecina/StayPuft), which is a fork of Casper the default theme for [Ghost](https://github.com/tryghost/ghost/).

## Features
- Responsive design.
- ~Post comments using [Disqus](http://disqus.com/).~
- Post comments using Google+ Comments
- In-site search using [GhostHunter](https://github.com/i11ume/ghostHunter).
- Support for [Font Awesome](https://github.com/FortAwesome/Font-Awesome)4.5.
- Basic support for [slidr.js](https://github.com/bchanx/slidr).
- Syntax highlighting using [Prism](https://github.com/LeaVerou/prism/) (Customized for this theme).

## Demo
This theme is being used in my [blog](https://fynx.me).

## Discussion
- The appropriate place to report problems is the [Issues section](https://github.com/thefynx/StayPuft-Dark/issues).

## Ghost Version
StayPuft tries to match Casper's version numbering system. That is, StayPuft version A.B.C should roughly have the same (or more) features as Casper version A.B.C. Features and bug fixes may be added between major versions, so the best way to stay updated is to clone and pull changes from the repo.

**The current StayPuft version is 1.2.5, and is expected to work with Ghost 0.7.0.**

If the current version of StayPuft is not compatible with the version of Ghost you're running, try looking for an older one in the [Releases section](https://github.com/thefynx/StayPuft-Dark/releases).

## Installation
- Clone this repository inside your themes folder:

```
cd ghost/content/themes
sudo git clone https://github.com/thefynx/StayPuft-Dark
```

- Copy all files in `partials` folder ending in `example` so they end in `hbs`:

```
cd StayPuft-Dark/partials
cp copyright.hbs.example copyright.hbs
cp sidebar-external.hbs.example sidebar-external.hbs
```

- Replace `partials/copyright.hbs` with your own disclaimer.
- Modify `partials/sidebar-external.hbs` with your own external links.
- Restart Ghost.
- Select the theme in your Settings page.

## Copyright & License
Original Copyright (c) 2013-2015 Ghost Foundation - Released under The MIT License.<br>Modifications Copyright (c) 2014-2015 David Lecina Fuentes - Released under The MIT License. Modifications to Modifications Copyright (c) 2016 Levi Smith - Released under The MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
