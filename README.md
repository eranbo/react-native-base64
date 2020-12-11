If you find this package useful hit the star with <3
  
# react-native-base64
Base64 encoding and decoding helping util (does not support some Unicode characters).  
Created for React Native but can be used anywhere.

Install  
```npm install --save react-native-base64```  
You can find it on npmjs.com here: [https://www.npmjs.com/package/react-native-base64](https://www.npmjs.com/package/react-native-base64)

How to use:
```
import base64 from 'react-native-base64'

...

base64.encode('Some string to encode to base64');

base64.decode('SW4gbXkgZXllcywgaW5kaXNwb3NlZA0KSW4gZGlzZ3Vpc2VzIG5vIG9uZSBrbm93cw0KUklQIEND==');

base64.encodeFromByteArray(byteArray: Uint8Array);

```

Do you like this package? Do you find it useful?  
Please rank it with a star and leave a comment.  
Thanks :)
