[![Build Status](https://travis-ci.org/lap00zza/9anime-Companion.svg?branch=master)](https://travis-ci.org/lap00zza/9anime-Companion)
[![Build status](https://ci.appveyor.com/api/projects/status/glkjys3aw8y9m8vb/branch/master?svg=true)](https://ci.appveyor.com/project/lap00zza/9anime-companion/branch/master)
[![bitHound Overall Score](https://www.bithound.io/github/lap00zza/9anime-Companion/badges/score.svg)](https://www.bithound.io/github/lap00zza/9anime-Companion)
[![Greenkeeper Badge](https://badges.greenkeeper.io/lap00zza/9anime-Companion.svg)](https://greenkeeper.io/)

<hr>

* 9anime Companion is tested and runs on: (*pr's are welcome to expand this*)

  Chrome | Firefox
  -------|--------
  60+    | 55+

<hr>

<h1 align="center">
  9anime Companion
</h1>
<p align="center"><em>A simple companion extension for 9anime</em></p>
<p align="center">
    <img src="https://image.ibb.co/jHMahQ/9ac_popup.png" height="350px" width="auto" alt="Popup">
</p>

## Features
* Remove Ads/Popups <sup>[1]</sup>
* Download All episodes
* MyAnimeList Integration
* Utility Bar
* Recently Watched list
* Toggle page elements (comments, you may also like etc.)
* Helpful shortcuts
  * <kbd>s</kbd> - Alternate search overlay (global)
  * <kbd>t</kbd> - Quickly scroll to player (only watch page)
* *and quite a few more..*
 
[1]: In my tests it removed 100% ads/popups without the need for an external adblocker. *Tested in Google Chrome Version 60.0.3112.90 (Official Build) (64-bit)*

## Download
* The latest passing build of 9anime Companion can be [downloaded from appveyor](https://ci.appveyor.com/project/lap00zza/9anime-Companion/build/artifacts?branch=master). *Remember that the builds are quite frequent.*
* Want to build it yourself? check out the [Build Instructions](#build-instructions)
* **Chrome Webstore**: https://chrome.google.com/webstore/detail/9anime-companion/fopcehkidabibdmachbcpbgllhehknah
* **AMO**: https://addons.mozilla.org/en-US/firefox/addon/9anime-companion/versions/beta

*Firefox users please check the developement channel (the one linked above). AMO review process is quite long so it is possible that the firefox version is behind the chrome version. If you want the latest features you can build the extension yourself.*

## Build Instructions
1. Install NodeJS
2. Install git
3. Run the following commands
   ```shell
   # Clone the repository
   $ git clone https://github.com/lap00zza/9anime-Companion.git
    
   # install dependencies
   $ npm install
 
   # Build the extension. If gulp command is not working, it means 
   # you dont have gulp-cli. You can either download gulp-cli or use
   # npm run build.
   $ gulp
   ```
4. Check `dist/chromium` and `dist/firefox` for the built extension.
5. *Optional:* since the project is in Typescript, be sure to use a editor like [VSCode](https://code.visualstudio.com/) to take full advantage.
6. *Optional:* check out the instructions for [Running in Developement Mode](https://github.com/lap00zza/9anime-Companion/wiki/Running-in-Developement-Mode)

> :information_source: Check `gulpfile.js` and `package.json` for all the available tasks

## Want to contribute?
Check out [CONTRIBUTING.md](https://github.com/lap00zza/9anime-Companion/blob/master/.github/CONTRIBUTING.md)

## Credits
* [Contributors](https://github.com/lap00zza/9anime-Companion/graphs/contributors)
* [SVG Loaders](https://github.com/SamHerbert/SVG-Loaders) by [Sam Herbert](https://github.com/SamHerbert)


## License
[MIT](https://github.com/lap00zza/9anime-Companion/blob/master/LICENSE)

Copyright (c) 2017 Jewel Mahanta
