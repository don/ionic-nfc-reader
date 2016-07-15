# PhoneGap NFC Reader

This project demonstrates reading NFC tags using [Apache Cordova](http://cordova.io) and [phonegap-nfc](https://github.com/chariotsolutions/phonegap-nfc).

This is an [Ionic Framework](http://ionicframework.com/) port of [phonegap-nfc-reader](https://github.com/don/phonegap-nfc-reader)

Your computer needs to be set up for Cordova and Android development.

Install Ionic 1.x

    $ npm install -g ionic

Install Plugin and Platform

    $ ionic platform add android
    $ ionic plugin add phonegap-nfc

Plug in your NFC enabled Android phone and run the app

    $ ionic run --device
