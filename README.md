# Repro

This *does not* reproduce the issue, but I will update this repo if I find a way to do so.

## Versions:

* stream-chat-react-native-core@3.9.0
* stream-chat-react-native@3.9.0
* stream-chat@~3.13.1

## To run this app:

1. Install dependencies (`yarn install && (cd ios && pod install)`)
2. Update `API_KEY` and `USER_TOKEN` in [App.tsx](./App.tsx)
3. Run the metro bundler (`yarn start &` or `yarn start` in a separate window)
4. Build the iOS app (`yarn ios`)
