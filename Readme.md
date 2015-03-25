jtray [![BuildStatus](https://travis-ci.org/ForNeVeR/jtray.png?branch=develop)](https://travis-ci.org/ForNeVeR/jtray)
=====
jtray is an system tray notifier of [Jenkins](http://jenkins-ci.org/) state.

## Build
Build system uses [Gradle](https://gradle.org/), you need to install that. After that, issue a terminal command

    $ gradle build

## Configuration
All configuration data is read from the `./jtra.properties` file. It should be in a [Java Properties file
format](http://docs.oracle.com/cd/E23095_01/Platform.93/ATGProgGuide/html/s0204propertiesfileformat01.html). There is an
example in `jtray.properties.example`.

## Testing
To test the application, run the following command:

    $ gradle run -DmainClass=me.fornever.jtray.TestApplication
