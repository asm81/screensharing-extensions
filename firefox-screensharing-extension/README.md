firefox-screensharing-extension
==============================

This extension is designed to allow the screen sharing feature for WebRTC applications on given domains

=

You can test this extension on Bistri Conference Demo:

* http://bistri.com/demo/conf

=

**Clone this extension, then:**

** Open `install.rdf`**

* line 4: modify the id attribute
* line 6: modify the name attribute
* line 10: modify the creator attribute
* line 11: modify the homepageURL attribute

** Open `bootstrap.js`**

* line 3-8: set all domains allowed to use this extension

** Create the xpi file ( Firefox extension format ) **

* zip the extension source files (and not the folder that contains files !)
* rename your file extension.zip into extension.xpi

## Pre-requisites

* Your application/website must be configured to use SSL.

## How to publish your extension

* Follow Mozilla instructions to package the extension : https://addons.mozilla.org/en-US/developers

## How to find my extension id

* After having published your extension, go to your add-on page
* Then right click on the "Add to Firefox" button and click "Copy link location" and paste it the URL in a text editor
* Your extension id appears in bold in the following url: addons.mozilla.org/firefox/downloads/latest/**592948**/addon-**592948**-latest.xpi?src=dp-btn-primary

## Note

You can use this extension within any WebRTC applications, it is vendor independant except for modification about allowed domains in `bootstrap.js`
