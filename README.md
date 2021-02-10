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
  implementation 'com.github.KrystilizeNevaDies:libjsimplex:135516348d'
}
```

Maven:
```
  <dependency>
	  <groupId>com.github.KrystilizeNevaDies</groupId>
	  <artifactId>libjsimplex</artifactId>
	  <version>135516348d</version>
	</dependency>
```
