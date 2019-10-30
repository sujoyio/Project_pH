# Portrait Helper
This app helps to organize portrait photos in the "/DCIM/Camera" folder created by Google Camera.

## Maintainers
This project is mantained by:
* [Sujoy Ghosh](http://github.com/sujoyself)

## Installation
Clone this repository and import into **Android Studio**
```
$ git clone https://github.com/sujoyself/PortraitHelper.git
```

## Configuration
### Keystores:
Create `app/keystore.gradle` with the following info:
```gradle
ext.key_alias='...'
ext.key_password='...'
ext.store_password='...'
```
And place both keystores under `app/keystores/` directory:
- `playstore.keystore`
- `stage.keystore`
