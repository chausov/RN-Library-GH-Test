
# react-native-native-library-toast-gh

## Getting started

`$ npm install react-native-native-library-toast-gh --save`

### Mostly automatic installation

`$ react-native link react-native-native-library-toast-gh`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-native-library-toast-gh` and add `RNNativeLibraryToastGh.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNNativeLibraryToastGh.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNNativeLibraryToastGhPackage;` to the imports at the top of the file
  - Add `new RNNativeLibraryToastGhPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-native-library-toast-gh'
  	project(':react-native-native-library-toast-gh').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-native-library-toast-gh/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-native-library-toast-gh')
  	```


## Usage
```javascript
import RNNativeLibraryToastGh from 'react-native-native-library-toast-gh';

// TODO: What to do with the module?
RNNativeLibraryToastGh;
```
  