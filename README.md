# SimplexNoiseJava ``2023.1.2``
Based on example code by Stefan Gustavson (stegu@itn.liu.se).

Optimisations by Peter Eastman (peastman@drizzle.stanford.edu).

Searching for the SimplexNoise C++ project? -> https://github.com/SRombauts/SimplexNoise

- - -
Added seed support by Daniel Niesmann (daniel.niesmann@outlook.com) in 2023.


How to implement (Maven/Gradle)
---
Maven repository:
```
<repositories>
    <repository>
        <id>jitpack</id>
        <url>https://jitpack.io</url>
    </repository>
    <!--Other repositories...-->
</repositories>
```
Maven dependency:
```
<dependencies>
    <dependency>
        <groupId>com.github.danieldieeins</groupId>
        <artifactId>SimplexNoiseJava</artifactId>
        <version>2023.1.2</version>
        <scope>compile</scope>
    </dependency>
    <!--Other dependencies...-->
<dependencies>
```
-
Gradle repository:
```
repositories {
    maven { url 'https://jitpack.io' }
    //Other repositories...
}
```
Gradle dependency:
```
dependencies {
    implementation 'com.github.danieldieeins:SimplexNoiseJava:2023.1.2'
    //Other dependencies...
}
```
