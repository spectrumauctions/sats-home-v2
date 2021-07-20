---
layout: page
title: SATS Java API 
permalink: /sats-java
nav_order: 30
---

# SATS Java API

SATS provides two APIs: 
The **Core API** to generate auction instances 
and the **Optimization API**, which extends the Core API by solving the winner determination problems.

## Getting started
Both APIs are bundled in one package and deployed on Maven Central. Hence, with Maven, including sats is as easy as:

    <dependency>
      <groupId>org.spectrumauctions</groupId>
      <artifactId>sats</artifactId>
      <version> --INSERT-LATEST-VERSION-HERE-- </version>
    </dependency>
    
This is enough information for Maven to download the dependency automatically.

Alternative without Maven:
The pre-compiled jar files are also available on [github](https://github.com/spectrumauctions/sats/releases). You can include them in your project directly.

## Examples
To see how to use the respective APIs, check out the examples on GitHub:

- [Core API examples](https://github.com/spectrumauctions/sats/tree/master/src/test/java/org/spectrumauctions/sats/core/examples)
- [Optimization API examples](https://github.com/spectrumauctions/sats/tree/master/src/test/java/org/spectrumauctions/sats/opt/examples)
