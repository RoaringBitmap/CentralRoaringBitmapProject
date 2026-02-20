## CentralRoaringBitmapProject

This is a demonstration of how to use the RoaringBitmap library from Maven Central.

- [Maven](#maven)
- [Gradle](#gradle)


## Maven

Add the following dependencies to your pom.xml file...

```xml
<dependency>
    <groupId>org.roaringbitmap</groupId>
    <artifactId>RoaringBitmap</artifactId>
    <version>1.6.9</version>
</dependency>
<dependency>
    <groupId>org.roaringbitmap</groupId>
    <artifactId>bsi</artifactId>
    <version>1.6.9</version>
</dependency>
```

## Gradle

The approach with gradle is similar.

All you need is to edit your `build.gradle` file like so:

```groovy
plugins {
    id 'java'
}

group 'org.roaringbitmap' // name of your project
version '1.0-SNAPSHOT' // version of your project

repositories {
    mavenCentral()
}

dependencies {
    implementation 'org.roaringbitmap:RoaringBitmap:1.6.9'
    implementation 'org.roaringbitmap:bsi:1.6.9'
    testImplementation 'junit:junit:3.8.1'
}
```
