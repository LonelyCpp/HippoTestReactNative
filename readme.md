## setup

- have `node.js`, `npm` and `yarn` installed
- run "yarn" in the root directory to install dependencies.

## run the ios project

```
cd ios
pod install
open HippoTestReactNative.xcworkspace
(run in xcode)
```

## to run the project successfully (for sanity)

1. remove `pod 'Hippo'` line from `ios/Podfile`
2. run `pod install`
3. open the `HippoTestReactNative.xcworkspace`
4. clean and build
