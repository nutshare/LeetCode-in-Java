# LeetCode-in-Java

[![Maven Central](https://img.shields.io/maven-central/v/com.github.javadev/leetcode-in-java.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.github.javadev%22%20AND%20a%3A%22leetcode-in-java%22)
[![Java CI](https://github.com/javadev/LeetCode-in-Java/actions/workflows/maven.yml/badge.svg)](https://github.com/javadev/LeetCode-in-Java/actions/workflows/maven.yml)
[![CodeQL](https://github.com/javadev/LeetCode-in-Java/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/javadev/LeetCode-in-Java/actions/workflows/codeql-analysis.yml)
[![javadoc](https://javadoc.io/badge2/com.github.javadev/leetcode-in-java/javadoc.svg)](https://javadoc.io/doc/com.github.javadev/leetcode-in-java)
[![Known Vulnerabilities](https://snyk.io/test/github/javadev/leetcode-in-java/badge.svg?targetFile=pom.xml)](https://snyk.io/test/github/javadev/leetcode-in-java?targetFile=pom.xml)

Java Solution for LeetCode algorithm problems, continually updating.

## Installation

Include the following in your `pom.xml` for Maven:

```xml
<dependencies>
  <dependency>
    <groupId>com.github.javadev</groupId>
    <artifactId>leetcode-in-java</artifactId>
    <version>1.3</version>
  </dependency>
  ...
</dependencies>
```

Gradle:

```groovy
implementation 'com.github.javadev:leetcode-in-java:1.3'
```

#### Tips and Tricks

* format code
    * `gradlew spotlessJavaApply`
* check formatting
    * `gradlew spotlessJavaCheck`
