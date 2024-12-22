# Android-development

## Overview - Interview 
==> framework for developing mobile and Ios application
==> written in javascript with react
==> initial release date:26 march 2015
==> maintained by facebook

## Installation
==> install choco,node and JDK

===> choco :- https://docs.chocolatey.org/en-us/choco/setup/#more-install-options
`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`

===> node and JDK :-https://reactnative.dev/docs/set-up-your-environment?platform=android
`choco install -y nodejs-lts microsoft-openjdk17`

## Setting up first application
npx @react-native-community/cli init <project-name>

## Run you android/ios application
npx react-native run-android
npx react-native run-Ios

## files and folders
 - `metro.config.js` - fast reload/compile the application
 - `bable.config.js` - Babel is a free, open-source JavaScript compiler that allows developers to use the latest JavaScript syntax in older browsers. as a code translator.
 - `chocolatey` - Chocolatey is a command-line package manager for Windows that simplifies the process of downloading and installing software, uses the NuGet packaging infrastructure and Windows PowerShell to make it easier to get software onto your machine.
 - `GemFile` - it is for ruby, for debug the application.
 - `watchman.config` - it checks any changes in code, it yes then it inform to metro.config.js
 - `buckconfig` - defines which plateform u are supporting in your application

## View, Text and Button
view works like div, but in view you can not write text.
 - <View>
        content here...
   </View>

if you want to write text/string then you have to use the Text component
 - <Text style={{fontSize:20,color:"red"}}>Hello aman, this is your first view of your application </Text>

and if you want to add button we have to write like this-
 - `<Button title='Click me' onPress={()=>console.log("hello")}/>`

## Interview
==> React native works with react
==> written in javascript with react
==> intial release: 26 march 2015
==> maitained by facebook
==> react is a library
==> react native is a framework

