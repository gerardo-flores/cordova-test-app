## Prerequisites

#### Mac
Since this solution targets both an iOS application and a browser, a Mac is required to build this application.

#### Node
Install via the [Node Website](https://nodejs.org/en/download/) or your package manager of choice (Homebrew, Mac Ports, etc.)

#### Cordova
Once Node is installed, at command line run `npm install -g cordova@6.3.1`.

#### Git
[Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) is required to clone this repository.

#### XCode
Required to compile this application for iOS and run it in a simulator.

## Setup

1. Clone this repository
2. From a terminal with the working directory being this cloned repo, run the commands below:
*  `cordova clean`
*  `cordova prepare` to pull down the supported Cordova platforms and plugins

## Run
* To run the application on a browser `cordova run browser`
* To run the application in an iOS simulator `cordova run ios`

You will see a web site that has the title "Test application: iOS and browser".  If the text "Device is Ready" is blinking, it's
an indication that the Cordova app has been initialized and is ready to use on both a browser and iOS.  In a browser the button 
will not do anything,  but in a device you'll hear two beeps.