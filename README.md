### Challenge: GoRestaurant Mobile
Small application developed using [React Native](https://reactnative.dev/) which connects to a Fake API, displays and filters the food dishes and allows the creation of new orders.

### Running Locally

```sh
# install packages
yarn

# if emulating on iOS, navigate into 'ios' folder and run
pod install

# start fake API server
yarn json-server server.json -p 3333

# start emulator on iOs
react-native run-ios

# or Android
react-native run-android
```
