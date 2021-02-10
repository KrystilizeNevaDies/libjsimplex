# libjsimplex
Java library for calculating simplex noise.

Uses the Aparapi library as a dependency:
https://code.google.com/p/aparapi/

More information and JAR download link can be found in the wiki page:
https://github.com/JaanJanno/libjsimplex/wiki

# How to use this lib as a dependency

Gradle:
```
repositories {
  // Use jcenter for resolving dependencies.
  jcenter()
  
  // Use jitpack for compiling dependencies.
  maven { url 'https://jitpack.io' }
}
dependencies {
  implementation 'com.github.KrystilizeNevaDies:libjsimplex:ec1d0db23e'
}
```

Maven:
```
// Repo
<repositories>
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
</repositories>

// Add dependency
<dependency>
  <groupId>com.github.KrystilizeNevaDies</groupId>
  <artifactId>libjsimplex</artifactId>
  <version>ec1d0db23e</version>
</dependency>
```


Refer to https://jitpack.io/#KrystilizeNevaDies/libjsimplex/ec1d0db23e for any issues
