# upgrade version react native safely


## terminal guide
**watchman watch-del-all**

**rm -rf package-lock.json**

**rm -rf yarn.lock**

**npm cache clean --force**

**sudo rm -rf node_modules && npm install --legacy-peer-deps**

**rm -rf $TMPDIR/metro-* && rm -rf $TMPDIR/haste-map-***

**sudo npx react-native upgrade 0.67.0**

  ****(before run this, delete package-lock.json first)

**sudo rm -fr android/app/build/**


## How to upgrade manually if there is file can not be override using react-native upgrade
1. use https://react-native-community.github.io/upgrade-helper/
2. don't forget to type your app name on react native helper 
3. copy & paste, add, or delete (file, part of code) are not change yet

<img width="1422" alt="image" src="https://github.com/Yosteven97/upgrade-react-native-version-safely/assets/33284223/1293e8de-3ace-4e61-94a6-ab42898b13cb">
