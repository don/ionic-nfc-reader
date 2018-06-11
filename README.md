# PhoneGap NFC Reader

This project demonstrates reading NFC tags using [Apache Cordova](http://cordova.io) and [phonegap-nfc](https://github.com/chariotsolutions/phonegap-nfc).

This is an [Ionic Framework version 1](http://ionicframework.com/) port of [phonegap-nfc-reader](https://github.com/don/phonegap-nfc-reader).

Your computer needs to be set up for Cordova and Android development.

Install Ionic

    npm install -g ionic

Clone the project

    git clone https://github.com/don/ionic-nfc-reader.git
  
Plug in your NFC enabled Android phone. Then build and run the app.

    cd ionic-nfc-reader/
    ionic cordova run android --device

Note this is an old Ionic v1 project. It was updated in June 2018 to run with the newer Ionic v3 command line tools which still support Ionic v1. 

Most of the code in this project is generated boilerplate. The files I modified are

* [www/index.html](www/index.html)
* [www/js/app.js](www/js/app.js)
* [www/js/filters.js](www/js/filters.js)
* [www/css/style.css](www/css/style.css)

If you're starting a new project with Ionic v3, take a look at the [Ionic Native wrappers for phonegap-nfc](https://ionicframework.com/docs/native/nfc/).
