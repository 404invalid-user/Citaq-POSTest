# POS Print tester

this is an example app to demonstrate the use of capacitor-plugin-serialprinter and capacitor-plugin-ledcontrol for your Citaq H10-X

tested and developed on a H10-1 but they seem to all be the same so it should work for you.

## get the apk

[click here to download it](https://github.com/404invalid-user/Citaq-POSTest/releases/download/0.0.1/app-debug.apk)

## dev setup

all the code is located under App.vue in the src folder everything is pretty self explanatory 

you need android studio installed

i would also change the package name

```
npm i --force
npm run build
npx cap sync
npx cap open android
```


