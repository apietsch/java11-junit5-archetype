# Java 17 + Kotlin 1.8 + JUnit 5 Quick Start Maven Archetype

forked and adapted from https://github.com/franz-see/junit5-archetype

Maven archetype to create a project configured for Java 17, Kotlin and using JUnit 5.

## Install archetype in local repository

Once you have cloned the repository locally. Just run the maven command below to install the archetype.

``` shell
mvn install
```

## Example using the archetype

When the archetype has been installed locally you can create a project using the command below. Just replace the parameter values with the actual values you want to use.

``` shell
 mvn archetype:generate -DarchetypeGroupId=be.pengo.archetypes \
                        -DarchetypeArtifactId=java17-junit5-archetype \
                        -DarchetypeVersion=1.1.0-SNAPSHOT
                        -DgroupId=be.pengo.kata.stringcalculator \
                        -DartifactId=stringcalculator \
                        -Dversion=1.0.0-SNAPSHOT \
                        -DinteractiveMode=false
```

## References

This will create a maven project from scratch that is configured for JDK8, and JUnit5. In its test directory, it will also contain several feature showcase for JUnit5:

Assertions
Assumptions
@Disabled
@DisplayName
Dynamic Tests
Parameterized Tests
Repeated Tests
@BeforeAll, @BeforeEach, @AfterEach, @AfterAll
TestInfo
Tests Tagging
Nested tests
Test Lifecycle
