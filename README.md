# react-native-share-pdf

## Getting started

`$ npm install react-native-share-pdf --save`

### Mostly automatic installation

`$ react-native link react-native-share-pdf`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.maximegerbe.reactnative.sharefile.SharePdfPackage;` to the imports at the top of the file
  - Add `new SharePdfPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-share-pdf'
  	project(':react-native-share-pdf').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-share-pdf/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-share-pdf')
  	```


## Usage
```javascript
import SharePdf from 'react-native-share-pdf';

// TODO: What to do with the module?
SharePdf;
```
