## Minimal Reproduction For 'RCAActionProtocol.h' file not found bug

This is a React Native app using Expo, Expo Dev Client, and `@stytch/react-native`. 

## Steps to reproduce

1. Clone this repository and install using: ```yarn```
2. Build the native iOS directory using Expo: ```npx expo prebuild --platform ios```
3. Build the iOS application using Expo: ```npx yarn run ios```
4. Observe build failure/error:
```
   
   ❌  (ios/Pods/Target Support Files/StytchReactNativeModule/StytchReactNativeModule-umbrella.h:14:9)

  12 | 
  13 | #import "StytchReactNativeModule.h"
> 14 | #import "RCAActionProtocol.h"
     |         ^ 'RCAActionProtocol.h' file not found

```
