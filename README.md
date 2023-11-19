<p align="center">
  <img src='./.assets/jf-automation-testing.jpg' width='200' align="center">
</p>

Apache JMeter, an Open Source Java application designed to measure performance and load test applications.

## What Is It?

Apache JMeter can measure performance and load test static and dynamic web applications.

It can be used to simulate a heavy load on a server, group of servers,
network or object to test its strength or to analyze overall performance under different load types.

## Requirements

The following requirements exist for running Apache JMeter:

- Java Interpreter:

  A fully compliant Java 8 Runtime Environment is required
  for Apache JMeter to execute. A JDK with `keytool` utility is better suited
  for Recording HTTPS websites.

- Optional jars:

  Some jars are not included with JMeter.
  If required, these should be downloaded and placed in the lib directory
  - JDBC - available from the database supplier
  - JMS - available from the JMS provider
  - [Bouncy Castle](https://www.bouncycastle.org/) -
  only needed for SMIME Assertion

- Java Compiler (*OPTIONAL*):

  A Java compiler is not needed since the distribution includes a
  precompiled Java binary archive.
  > **Note** that a compiler is required to build plugins for Apache JMeter.

## Installation Instructions

> **Note** that spaces in directory names can cause problems.

- Release builds

  Unpack the binary archive into a suitable directory structure.

## Running JMeter

1. Change to the `bin` directory
2. Run the `jmeter` (Un\*x) or `jmeter.bat` (Windows) file.

## Documentation

The documentation available as of the date of this release is
also included, in HTML format, in the [printable_docs](printable_docs) directory,
and it may be browsed starting from the file called [index.html](printable_docs/index.html).
