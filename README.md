# react-native-base64
Base64 encoding and decoding helping util (does not support some Unicode characters).  
Created for React Native but can be used anywhere.

Install  
```npm install --save react-native-base64```  

How to use:
```
import base64 from 'react-native-base64'

...

base64.encode('Some string to encode to base64');

base64.decode('SW4gbXkgZXllcywgaW5kaXNwb3NlZA0KSW4gZGlzZ3Vpc2VzIG5vIG9uZSBrbm93cw0KUklQIEND==')
```

