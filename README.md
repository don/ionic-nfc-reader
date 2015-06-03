# PhoneGap NFC Reader

This project demonstrates reading NFC tags using [Apache Cordova](http://cordova.io) and [phonegap-nfc](https://github.com/chariotsolutions/phonegap-nfc).

This is an [Ionic Framework](http://ionicframework.com/) port of [phonegap-nfc-reader](https://github.com/don/phonegap-nfc-reader)

Your computer needs to be set up for Cordova and Android development.

Install Plugin and Platform

    $ cordova platform add android
    $ cordova plugin add com.chariotsolutions.nfc.plugin


This version has an MimeTypeListener to handle NDEF messages from an intent filters that launched the app. The intent filter is defined in AndroidManifest.xml.

Add this to platform/android/AndroidManifest.xml

    <intent-filter>
        <action android:name="android.nfc.action.NDEF_DISCOVERED" />
        <category android:name="android.intent.category.DEFAULT" />
        <data android:scheme="http" android:host="example.com" android:pathPrefix="" />
    </intent-filter>


Plug in your NFC enabled Android phone and run the app

    $ cordova run


See https://github.com/chariotsolutions/phonegap-nfc/issues/187 for more info.
