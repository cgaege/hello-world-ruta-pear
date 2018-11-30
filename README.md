# hello-world-ruta-pear [![Build Status](https://travis-ci.com/cgaege/hello-world-ruta-pear.svg?branch=master)](https://travis-ci.com/cgaege/hello-world-ruta-pear)

An Apache UIMA Hello World Annotator written in RUTA bundled as a PEAR package

This project provides a minimal example how to automatically generate a UIMA descriptor and a UIMA type system for your RUTA script and bundle it as a self contained UIMA PEAR package. It contains a RUTA script that adds a simple hello world annotation with a greeting to the document text.

## Build prerequisites

- JDK 1.8 or later
- Maven 

## Build instructions
    mvn clean install