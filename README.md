# rwdemail
This Fork uses LESS instead of SASS for Stylesheets.
Responsive or Basic Email Development in a box! Automate Everything, from LESS precomiling, CSS Inlining, CSS/HTML and Image Minification, S3 Image Hosting and [Litmus](https://litmus.com) email testing. With the help of [INK templates](http://zurb.com/ink/docs.php) and its CSS boilerplate, designing emails of any kind is a breeze.

## Features
* Image Optimization with [jpegtran](http://jpegclub.org/jpegtran/) and [OptiPNG](http://optipng.sourceforge.net/)
* HTML templating with [EJS](https://github.com/visionmedia/ejs) and [more](https://github.com/dwightjack/grunt-ejs-render)
* LESS stylesheets with [LESS](http://lesscss.org/)
* Inlining CSS styles with [Email-Builder](https://github.com/yargalot/Email-Builder)
* CSS/HTML Minification
* Local Test Server with [Connect](https://github.com/gruntjs/grunt-contrib-connect)
* Automated [Litmus](https://litmus.com) Email Tests with [Email-Builder](https://github.com/yargalot/Email-Builder)
* HTML/CSS Responsive Email Framework with [Zurb's INK](http://zurb.com/ink/)

## Getting started 
If you haven't used [Node](http://nodejs.org/) or [Grunt](http://gruntjs.com/getting-started) before, please read the documentation for each to become familiar with them. This plugin uses both Node and Grunt along with other requirements which are listed below.

After cloning this repo and installing all requirements, run
```shell
npm install
```

To launch example email template on a Node.js server, run
```shell
grunt dev
```

## Litmus Applications
Have a peak at this [XML feed](https://klick9.litmus.com/emails/clients.xml) for the testing client available to your account and then update the **grunt-config.json** file.

## Requirements
* **On OSX:** Xcode
* **On Windows:** MS Visual Studio 2012 for Windows Desktop (Express version works well)
* Grunt-cli >= 0.1.7 and Grunt >=0.4.2 (`npm install grunt-cli -g`)
* Python >= 2.7.6 && < 3.0.0 ([installers](https://www.python.org/downloads/))
  * **MUST be Windows binary. NOT x64**
* Ruby >= 1.9.3 ([installers](http://www.ruby-lang.org/en/downloads/))
  * Make sure to add Ruby executables to your PATH
* Node.js >= 0.10.20 ([installers](http://nodejs.org/download/)) ([install wiki](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager))
  * **MUST be 32-bit version. NOT 64-bit**

## Ink (http://zurb.com/ink/)
Supported Clients (may be outdated, please see [Ink Docs](http://zurb.com/ink/docs.php#compatibility))
* Apple Mail (Desktop)
* Apple Mail (iOS)
* Outlook (2000, 2002, 2003)
* Outlook (2007, 2010, 2013)
* Outlook (2011)
* Thunderbird
* Android
* Gmail (Desktop)
* Gmail (Mobile, iOS, Android)
* Outlook 2011 for Mac
* AOL Mail
* Hotmail
* Outlook.com

# Thanks
- [iDVB] (https://github.com/iDVB/rwdemail) where the the Plugin was forked and just changed slightly to be able to use LESS instead of SASS
- [dwitghtjack](https://github.com/dwightjack) for [grunt-email-boilerplate](https://github.com/dwightjack/grunt-email-boilerplate/blob/master/README.md) which this was based on
- [yargalot](https://github.com/yargalot) for [Email-Builder](https://github.com/yargalot/Email-Builder) which is used

## License
Copyright (c) 2014 Dan Van Brunt Licensed under the MIT license.

## To Do:
- suggestions welcome
- More stuff

