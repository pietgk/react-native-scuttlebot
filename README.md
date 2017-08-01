# Scuttlebot for React Native apps

## install

`npm install --save react-native-scuttlebot`

## usage

In your React Native application (e.g. index.android.js):

```js
import Scuttlebot from 'react-native-scuttlebot';

// ...

// When you're ready, this will spawn a node.js process in the background:
Scuttlebot.start();
```

### versions

If this package is version A.B.C, then it uses `scuttlebot@A.B.C`.
