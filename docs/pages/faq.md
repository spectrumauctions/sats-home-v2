---
layout: page
title: FAQ
permalink: /faq
nav_order: 70
---

# Frequently Asked Questions

## 1. What are the different ways ways to access SATS?
- Using the APIs in your own java code
Via the Core API, you gain access to the full feature set of SATS, including the ability to change all parameters of the value models, requesting values for the bundles on the fly, etc.
If you need to solve the winner determination problem for a generated auction instance, you can use Optimization API, which extends the Core API.
- Using the Python bridge in your own python code
If you prefer to use SATS in your Python project, you can access some of the features of SATS via PySats. For instructions on how to use this, check out the GitHub page.
- Using `sats.jar` as a command line tool
An executable jar, allowing the generation of auction instances (i.e., value files) in your command line. The available options allow for some parametrization of the generated value functions, yet not quite as much as when using the Core API.
- SATS Web Application
An easy-to-use web interface to generate auction instances (i.e., value files) directly in your browser, without having to install anything. The web interface allows for very light parametrization of the value models.

## 2. For which value models does SATS already contain the MIP formulation to solve the winner determination problem?
Currently, SATS includes a MIP for the following value models:

- Multi-Region Value Model (MRVM)
- Single-Region Value Model (SRVM)
- Local Synergy Value Model (LSVM)
- Global Synergy Value Model (GSVM)
