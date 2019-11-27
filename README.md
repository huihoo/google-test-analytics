Google Test Analytics
=================

This is a fork of the [Google Test Analytics project](https://testing.googleblog.com/2011/10/google-test-analytics-now-in-open.html).

How to build?
----------------
You need Maven (http://maven.apache.org) to build this project.

1. Clone this repo
2. Run 
>mvn package

How to run a development server?
-----------------

You can take a tour through test-analytics-ng by deploying it to a local Jetty instance.

>mvn appengine:devserver

Navigate to (http://localhost:8080)

Requirements
-----------------

I have successfully built and run this version of test-analytics using Java 8 and Maven 3.5 on a Mac. It does **not** build with newer versions of Java. There is a [pull request](https://github.com/martinschneider/google-test-analytics/pull/1) to upgrade the underlying frameworks and support Java 13]. Feel free to contribute!