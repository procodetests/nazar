# <p align="center"> Nazar </p>

<p align="center">
  <img alt="icon" src="https://i.imgur.com/tXJvMQg.png" width="120" height="120"> 
</p>

<p align="center">Electronic component detection system</p>

## Overview

Nazar is an app built with react-native with a little spice of Tensorflow which allows the user to take a picture using the camera or fetch image from gallery to identify the component with the predicted percentage ratio, thus using image processing and algorithm to segment them after detection.

It is done with both Clarifai API and Tensorflow frozen graph to deduce without internet along with option to look for feeds from internet with the app.

<p align="center">
    <a href="https://play.google.com/store/apps/details?id=com.speks.nazar" target="_blank"><img src="http://i.imgur.com/D5B4zOT.png" height="75"/></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://itunes.apple.com/us/app/" target="_blank"><img src="http://i.imgur.com/Akywpc7.png" height="75"/></a>
</p>

<p align="center">
  <img alt="screenshot_1" src="https://i.imgur.com/k8lG4Mn.png" width="200" height="356" style="margin-left: 10px">
  <img alt="screenshot_2" src="https://i.imgur.com/FVFjFlw.png" width="200" height="356" style="margin-left: 10px">
  <img alt="screenshot_3" src="https://i.imgur.com/By9qMwT.png" width="200" height="356" style="margin-left: 10px">
  <img alt="screenshot_4" src="https://i.imgur.com/BIktO0I.png" width="200" height="356" style="margin-left: 10px">
  <img alt="screenshot_4" src="https://i.imgur.com/6AzTqki.png" width="200" height="356" style="margin-left: 10px">
  <img alt="screenshot_4" src="https://i.imgur.com/syx3gRT.png" width="200" height="356" style="margin-left: 10px">
</p>


## Installation

Clone the source locally:
```
$ git clone https://github.com/aryaminus/nazar
$ cd nazar
```

**Create a .env file with**
```
CLARIFAY_KEY="your clarifai api key"
```

**Add assets by creating an `assets` folder in project root directory**
```
    dumbell.jpg
    tensorflow_inception_graph.pb
    tensorflow_labels.txt
```

**Start the application in development mode**
```
npm install
react-native link
react-native run android
```
or for VS-Code:
```
npm install
react-native link
```
then press F1 or Fn+F1 and React Native:Run Android on Device 

## References:
1. <a href="https://github.com/reneweb/react-native-tensorflow" target="_blank">react-native-tensorflow</a>
2. <a href="https://github.com/agrcrobles/react-native-live-translator" target="_blank">react-native-live-translator</a>
3. <a href="https://github.com/leonardoballand/seepizz" target="_blank">seepizz</a>
4. <a href="https://github.com/googlecodelabs/tensorflow-for-poets-2" target="_blank">tensorflow-for-poets</a>
5. <a href="https://facebook.github.io/react-native/docs/signed-apk-android.html" target="_blank">Generate Signed APK</a>

## Contributing

1. Fork it (<https://github.com/aryaminus/nazar/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request