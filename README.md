# upgrade version react native safely

**watchman watch-del-all**

**rm -rf package-lock.json**

**rm -rf yarn.lock**

**npm cache clean --force**

**sudo rm -rf node_modules && npm install --legacy-peer-deps**

**rm -rf $TMPDIR/metro-* && rm -rf $TMPDIR/haste-map-***

**sudo npx react-native upgrade 0.67.0**

****(before run this, delete package-lock.json first)

**sudo rm -fr android/app/build/**
