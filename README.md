# Pride in London App

iOS: https://itunes.apple.com/gb/app/pride-in-london/id1250496471

Android: https://play.google.com/store/apps/details?id=org.prideinlondon.festival

### Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [Watchman](https://facebook.github.io/watchman/docs/install.html)
- [Install Yarn](https://yarnpkg.com/en/docs/install)
- `$ yarn global add react-native-cli`

More information on getting started can be found here: https://facebook.github.io/react-native/docs/getting-started.html under the `Building projects with React Native` tab.

#### General

Clone the repository

And install dependencies

`$ yarn`

## Running

### iOS

- `yarn run-ios [--simulator="iPhone X"]`

### Android

- `yarn run-android`

### Debugging

```bash
brew update && brew cask install react-native-debugger
```

Then to debug:

1.  Close any other debugger windows you have open
1.  Open the App from your Applications folder
1.  Start debugging in the app using one of the following methods:

| Platform    | Command                                                                           |
| ----------- | --------------------------------------------------------------------------------- |
| **iOS**     | Press Cmd+R to reload, Cmd+D or shake for dev.                                    |
| **Android** | Double tap R on your keyboard to reload, shake or press menu button for dev menu. |
