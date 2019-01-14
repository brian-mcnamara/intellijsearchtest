Simple IntelliJ search repo repository.

To repo, first run through a `mvn install` to generate all the artifacts.
next comment out moduleB in the root pom.xml so it will be included as a library.

After IntelliJ refreshes, search for usages of ClassA.

The expected result is to find ClassB which is a library pulled in by moduleC