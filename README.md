refer to this SO answer for more info http://stackoverflow.com/questions/44040154/ionic-inappbrowser-no-done-close-button-ios/44041272#44041272

### How to use this repo :

Download nodejs from https://nodejs.org/en/download/current/ and install node and npm

```bash
$ sudo npm install -g ionic cordova
```
clone this repository and run ```npm install```

Then, to run it in browser, use ```ionic serve``` or 
to run it in emulator/device

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

Substitute ios for android if not on a Mac.

