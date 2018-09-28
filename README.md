Java Inject API   [![][Maven Central img]][Maven Central] [![][Javadocs img]][Javadocs] [![][license img]][license]
===============
This library is a fork of the [JSR-330](https://github.com/javax-inject/javax-inject) specification.

Additionally, it has following changes:
* Added ```module-info.java```, so requires Java 9 or greater.
* Fixed HTML 5 errors in javadocs

**Documentation:** Latest javadocs is available [here](https://pustike.github.io/javax.inject/docs/api/).

Download
--------
To add a dependency using Maven, use the following:
```xml
<dependency>
    <groupId>io.github.pustike</groupId>
    <artifactId>javax.inject</artifactId>
    <version>1.1.0</version>
</dependency>
```
To add a dependency using Gradle:
```
dependencies {
    compile 'io.github.pustike:javax.inject:1.1.0'
}
```
Or, download the [latest JAR](https://search.maven.org/remote_content?g=io.github.pustike&a=javax.inject&v=LATEST)

License
-------
This library is published under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

[Maven Central]:https://maven-badges.herokuapp.com/maven-central/io.github.pustike/javax.inject
[Maven Central img]:https://maven-badges.herokuapp.com/maven-central/io.github.pustike/javax.inject/badge.svg

[Javadocs]:https://javadoc.io/doc/io.github.pustike/javax.inject
[Javadocs img]:https://javadoc.io/badge/io.github.pustike/javax.inject.svg

[license]:LICENSE
[license img]:https://img.shields.io/badge/license-Apache%202-blue.svg
