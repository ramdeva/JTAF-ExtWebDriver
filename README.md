JTAF-ExtWebDriver
==================

[Extensions for WebDriver](http://finraos.github.io/JTAF-ExtWebDriver/) improves upon the powerful WebDriver API with robust features that keep your browser automation running smoothly. This provides a widget library, improved session management and extended functions over the existing WebDriver API.

Here is the link to [getting started](http://finraos.github.io/JTAF-ExtWebDriver/howitworks.html)

Contributing
=============
We encourage contribution from the open source community to make ExtWebDriver better. Please refer to the [development](http://finraos.github.io/JTAF-ExtWebDriver/contribute.html) page for more information on how to contribute to this project.

Building
=========
ExtWebDriver uses Maven for build. Please install Maven by downloading it from [here](http://maven.apache.org/download.cgi).
```sh
# Clone ExtWebDriver git repo
git clone git://github.com/FINRAOS/JTAF-ExtWebDriver.git
cd JTAF-ExtWebDriver

# Run package to compile and create jar
mvn package
```

Running Tests
==============
ExtWebDriver uses Maven failsafe plugin to execute the integration tests. Each test runs against a locally deployed app (using Jetty server) using HtmlUnitDriver. You can execute all the tests by executing:
```sh
mvn verify
```
You can run individual tests by executing it from your IDE or through command line. You need to deploy the app locally first before executing your tests independently.

License Type
=============
JTAF projects including ExtWebDriver is licensed under [Apache License Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
