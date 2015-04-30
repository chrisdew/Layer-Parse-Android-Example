# Layer + Parse Android Example

This repository contains an example project that demonstrates how to implement an Android chat application with messaging services provided by [Layer](https://layer.com) and a user backend provided by [Parse](http://parse.com).

## Requirements

This application requires Android Studio. Dependencies are managed via maven to simplify installation.

## Setup

1. Clone the project from Github: `$ git clone https://github.com/layerhq/Layer-Parse-Android-Example.git`
2. Open the project in Android Studio.
3. In `LayerImpl.java` replace `LayerAppID` with the App ID from the Layer Dashboard (found under the Info section of your project)
4. In `ParseImpl.java` replace the `ParseAppID` and `ParseClientKey` with the Keys from the Parse Dashboard (found under Settings -> Keys)
5. Add the [Layer Parse Module](https://github.com/layerhq/layer-parse-module) to your Parse Cloud Code to serve as an authentication manager.
6. Build and run the application and tap the "Sign Up" button to create a new user and begin messaging!

For more in-depth documentation about this project, check our [guide](https://developer.layer.com/docs/guides/android#parse).

## Highlights

* Uses [Parse](https://www.parse.com) to authenticate and create new users.
* Demonstrates how to get identity tokens from Parse Cloud Code using the [Layer Parse Cloud Module](https://github.com/layerhq/layer-parse-module)
* Uses RecyclerViews to drive the Messaging UI Experience

## Credits

This project was lovingly crafted in San Francisco. At Layer, we are building the full-stack building block for communications. We value, support, and create works of Open Source engineering excellence.

* Neil Mehta
* Steven Jones

## License

Layer-Parse-iOS-Example is available under the Apache 2 License. See the LICENSE file for more info.
