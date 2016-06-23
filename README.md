# Gradle Build Scan Quickstart

<img src="http://bit.ly/28Pn68D" align="right" width="280" />

This is an example project that you can use to experience [Gradle Build Scans][gradle.com].

It is a small Java project that has the [Gradle Build Scan plugin][plugin] already applied.

## Create a Build Scan!

Follow these simple steps to create a Build Scan:

1. Clone this project
2. Read the [Terms of Service][terms-of-service]
3. Uncomment the Terms of Service agreement code in the `build.gradle` file
4. Run `./gradlew build -Dscan`

The build should end with something similar to:

    Publishing build information...
    https://gradle.com/s/ria2s2x5oaazq
    
Follow the green link shown at the end of the build to view your Build Scan.

Note: If you run a build without the `-Dscan` flag, no Build Scan will be created and 
no information will be sent.

## Next steps

Create different kinds of Build Scans by locally modifying this quickstart project. Here are some ideas:

- Edit `src/main/java/example/Example.java` to introduce compile errors
- Edit `src/test/java/example/ExampleTest.java` to introduce test failures
- Add more dependencies, more plugins, and more projects 

Alternatively, enable one of your own builds to produce Build Scans by following the [step-by-step instructions][instructions]. 
    
## Need help?

Talk to us on the <a href="https://discuss.gradle.org/c/help-discuss/cloud-services">Gradle Forum.</a>

If you are completely new to the Gradle Build Tool, start [here][gradle-download].

[gradle-download]: https://gradle.org/gradle-download
[plugin]: https://scans.gradle.com/plugin
[gradle.com]: https://www.gradle.com
[terms-of-service]: https://scans.gradle.com/terms-of-service
[instructions]: https://scans.gradle.com/setup/step-1
