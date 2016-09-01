[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=fuzzymannerz&url=https://github.com/fuzzymannerz/swmp&title=SWMP)
# SWMP - Server Web Monitor Page

**A responsive, eye-pleasing Linux server statistics dashboard.**
- [Screenshot](#non-fancy-fake-devices-screenshot-)
- [Requirements](#requirements)
- [Installation](#installation)
- [Themes](#themes)
- [Show Some Love <3](#show-some-love-3)
- [Credits & Acknowledgements](#credits--acknowledgements)


![](http://i.imgur.com/q8XWluS.png)

### Non-"Fancy fake devices" Screenshot. ;)
![](https://i.imgur.com/zAIBKkd.png)

## Requirements
- Linux OS with...
- A Web Server. (Nginx, Apache etc...)
- PHP with **shellexec()** and **exec()** enabled.

## Installation

### The Easy Way
Simply run `bash <(curl -s -L https://getswmp.thefuzz.xyz)` from your Linux command line and follow the setup steps.

### The Manual Way
1. [Download the Zip file](https://github.com/fuzzymannerz/swmp/archive/master.zip).
2. Extract the files to the web server. (You might want to secure access somehow, [.htpasswd](http://www.htaccesstools.com/htpasswd-generator/) maybe?)
3. Optionally copy the file `config.php` to `config.local.php` and adjust the settings for your web server.
4. That's it! (Unless you want to change the theme, in which case, read on!)

## Themes
SWMP includes a selection of themes. The default being **simplex**. (The red and white one above)
![](http://i.imgur.com/vlw9NyV.png)
To choose another theme, edit **config.local.php** and change line `"theme" => "slate"` to the theme of your choice. The choices are:    
_cerulean, cosmo, lumen, paper, readable, sandstone, simplex, slate, spacelab, superhero, united_ and _yeti_.    
All theme stylesheets are located in **~/css/themes/**.

## Show Some Love <3
If you make use of SWMP in some way, please consider a donation.    

**[PayPal](https://paypal.me/fuzzymannerz)**, **[Flattr](https://flattr.com/submit/auto?user_id=fuzzymannerz&url=https://github.com/fuzzymannerz/swmp&title=SWMP)**    
**BTC:** 1DUJH2kqccDpTHHSCXDkRGhxtvXm9PdnkN

## Credits & Acknowledgements
SWMP wouldn't be possible without the use of these awesome projects:

eZ Server Monitor Web:    
https://github.com/shevabam/ezservermonitor-web    
Gauge JS:    
http://github.com/bernii/gauge.js   
Tablesaw:    
https://github.com/filamentgroup/tablesaw    
Twitter Bootstrap:    
https://github.com/twbs/bootstrap    
Bootswatch:    
https://github.com/thomaspark/bootswatch    
jQuery:    
https://github.com/jquery/jquery    
