# HTML5 & JavaScript QR scanner powered by WebRTC
Simple-QR-scanner is based on [Instascan by Chris Schmich](https://github.com/schmich/instascan) which is powered by the [Emscripten JavaScript build](https://github.com/kig/zxing-cpp-emscripten) of the [C++ port](https://github.com/glassechidna/zxing-cpp) of the [ZXing Java library](https://github.com/zxing/zxing).
## Use
My 'version' of Instascan is optimized for mobile use, the preview of the camera is displayed full screen and the content decrypted from the QR code is shown right on the screen, no need for consoles or scrolling. As of July 2017 iOS devices are out of luck as Safari (but also Chrome and Firefox for iOS) will only be able to support WebRTC (a collection of communication protocols needed to access the camera) with iOS 11.
## In action
You can try out the scanner [here](https://timmedia.github.io/simple-QR-scanner/). Please allow your brwoser to access your camera.
## Instascan License
Copyright © 2016 Chris Schmich
MIT License. See [LICENSE](https://github.com/schmich/instascan/blob/master/LICENSE) for details.
