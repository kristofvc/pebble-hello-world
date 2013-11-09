Pebble Hello World
==================

This is a pebble hello world application started from the standard app skeleton and following the tutorial on https://developer.getpebble.com/1/GettingStarted/HelloWorld/. This is a tutorial for the pebble SDK 1, but it gives you a quick understanding of how things work.
This was only tested on a mac with OSX Mavericks, with a first generation pebble watch, coupled with an iPhone 5.


## Build and install

- Open XCode
- Make sure you've installed xcode command line tools
- Install the pebble SDK 2.0 (follow steps here https://developer.getpebble.com/2/)
- cmd + shift + 2 to open the organizer, or go to window > organizer
- Set your iphone as a developer device, you should then see the developer menu in your iphone settings app

- Open this page on your iphone https://developer.getpebble.com/2/
- Download and install the pebble application 2.0 (by clicking the link on the page in the previous step)
- Open settings on your phone, search for the pebble app and enable developer mode.
- Open the application
- Download the pebble firmware 2.0 and install it on your watch (also via the page on your phone)
- https://developer.getpebble.com/2/ check here if something goes wrong

- Now go to the "status" page in the pebble app on your phone and click on developer connection (this menuitem should now be visible)
- Take note of your iphone's IP address
 
- Clone this project on your computer and go to the project folder
- pebble build
- pebble install --phone PHONE_IP_ADDRESS

- Open the app on your watch

(Standard this app is set as a watchface, you can set is as a watchapp by editing appinfo.json)