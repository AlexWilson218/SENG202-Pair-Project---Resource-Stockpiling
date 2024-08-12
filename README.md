# SENG201 Blood, Sweat, and Tears Overview
Welcome to the README for Blood, Sweat, and Tears

## Authors
- SENG201 Teaching team
- Isaac Macdonald, ima97, 52503082
- Alex Wilson, awi218, 15599278

## Prerequisites
- JDK >= 17 [click here to get the latest stable OpenJDK release (as of writing this README)](https://jdk.java.net/18/)
- *(optional)* Gradle [Download](https://gradle.org/releases/) and [Install](https://gradle.org/install/)


## What's Included
This project comes with some basic examples of the following (including dependencies in the build.gradle file):
- JavaFX
- Junit 5

We have also included a basic setup of the Gradle project and Tasks required for the course including:
- Required dependencies for the functionality above
- Test Coverage with JaCoCo
- Build plugins:
    - JavaFX Gradle plugin for working with (and packaging) JavaFX applications easily

## Importing Project (Using IntelliJ)
IntelliJ has built-in support for Gradle. To import the game:

- Launch IntelliJ and choose `Open` from the start-up window.
- Select the project and click open
- At this point in the bottom right notifications you may be prompted to 'load gradle scripts', If so, click load

**Note:** *If you run into dependency issues when running the app or the Gradle pop up doesn't appear then open the Gradle sidebar and click the Refresh icon.*

## Run Project 
1. Open a command line interface inside the project directory and run `./gradlew run` to run the app.
2. The app should then open a new window, this may not be displayed over IntelliJ but can be easily selected from the taskbar

## Build and Run Jar
1. Open a command line interface inside the project directory and run `./gradlew jar` to create a packaged Jar. The Jar file is located at build/libs/seng201_team0-1.0-SNAPSHOT.jar
2. Navigate to the build/libs/ directory (you can do this with `cd build/libs`)
3. Run the command `java -jar seng_201_team0-1.0-SNAPSHOT.jar` to open the application.

## Run Tests
1. Open a command line interface inside the project directory and run `./gradlew test` to run the tests.
2. Test results should be printed to the command line

## Photo Credits
- Drill Sergeant - https://pxhere.com/en/photo/747033
- Camo Background - https://stock.adobe.com/nz/images/vector-camouflage-pattern-for-army-camouflage-military-pattern/420246493?prev_url=detail
- Shopping Cart - https://vectorportal.com/vector/shopping-cart-vector-image-2/14264

**Note:** *This Jar is **NOT** cross-platform, so you **must** build the jar you submit on Linux.* 