---
layout: page
title: SATS Command Line Interface
permalink: /sats-cli
nav_order: 25
---

# SATS Command Line Interface
Using the jar file directly, it's possible to generate auction instances (i.e., value files) via command line with limited parametrization options.
Its usage is described here.

Download the latest JAR from our [releases on github](https://github.com/spectrumauctions/sats/releases/download/v0.7.1/sats-0.7.1.jar)

## Example

    java -jar sats.jar --model MRVM --nationalbidders 3 --iterator RANDOM --bidsPerBidder 10
    
## Get Help

Two ways:
- Run ``java -jar sats.jar --help``
- Read the [docs](https://github.com/spectrumauctions/sats#getting-started-with-sats-as-a-command-line-tool)
