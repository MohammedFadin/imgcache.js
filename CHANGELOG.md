# Release Notes #

## 0.7.0 ##

### NEW ###
* New method: ImgCache.removeFile (#33)
* New method: ImgCache.getCurrentSize + added ability to clear cache on init when used space is higher than a given value (#28)
* New method: ImgCache.useBackgroundOnlineFile to revert a call to useCachedBackground (#17)
* jQuery/Zepto is not a required dependency anymore, if not available it will be using only the DOM API (#29)
* Added API coverage check in unit test

### IMPROVED ###
* Unit tests are moved to index.html
* README has been improved and split into multiple files: CORDOVA.md contains all documentation related to Cordova/Phonegap
* Reorganised code to be clearer + added checks throughout the code where missing
* Updated unit tests for 100% API coverage and multiple options configurations
* config.xml has been updated for newest Cordova releases requirements

### FIXED ###
* Fixed issues with Cordova 3.3/3.4 (#35, #40 -- thanks to Lukáš Marek)

## Older releases ##

* 0.6.2 Added extra checks to make sure ImgCache is properly initialised first (#15) + added note in README about Phonegap plugins (#25)
* 0.6.1 Added useCachedFileWithSource (#21) + added Bower package definition
* 0.6   Updated deprecated Chrome storage API + Refactored code + improved automated test suites + fixes
* 0.5.2 Fixed isCache for Android  + now works with Zepto + using new Chrome Blob
* 0.5.1 Fixed behaviour of isCached method
* 0.5   Added isCached method (thanks to David Novakovic)
* 0.4   Set cache files to not be backed up by iCloud (iOS only - requires Cordova 1.8+)
* 0.3   Added granularity to log entries + callbacks to all asynchronous methods + automated tests page
* 0.2   Cached filenames are now using hash of source url (SHA-1)
* 0.1   Initial release
