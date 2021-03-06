# AndroidAspectExample
Project to show examples of leveraging Aspect-Oriented Programming techniques

Aspects are defined in AspectLogging.java and affect MainActivity.java. 
In order to see that the code has been injected, build the app and check the app/build directory for the 
ajc-transform.log file which will show which advices have been added to the project during the build process.

If you run the app, the aspects added will simply log when a button is clicked or onCreate happens.

Created as a sample for the following Medium article:
[Aspect-Oriented Programming in Android](https://link.medium.com/XYs0fWKrC7)

### Releases
Please see the [GitHub Releases Page](https://github.com/jdvp/AndroidAspectExample/releases)
for this example if you want to see details for a specific Android Gradle Plugin version.