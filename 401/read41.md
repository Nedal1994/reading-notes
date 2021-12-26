# Read41 Summary

![react-native](https://miro.medium.com/max/1750/1*C3kxjCrJy-aWSMpe2chfaA.png)

React Native is a framework that builds a hierarchy of UI components to build the JavaScript code. It has a set of components for both iOS and Android platforms to build a mobile application with native look and feel. ReactJS, on the other hand, is an open source JavaScript library to create user interfaces. However, both React Native and ReactJS are developed by Facebook using the same design principles, except designing interfaces.

```
import React from 'react';
import { Text, View } from 'react-native';

const HelloWorldApp = () => {
  return (
    <View
      style={{
        flex: 1,
        justifyContent: "center",
        alignItems: "center"
      }}>
      <Text>Hello, world!</Text>
    </View>
  )
}
export default HelloWorldApp;
```

![expo](https://res.cloudinary.com/practicaldev/image/fetch/s--OK5nAo07--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/rmqgubejyi0rjkn87moo.png)

Expo is a framework and a platform for universal React applications. It is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.