# Maven builder for Spigot plugin

Simple Github Action for build a Spigot plugin with Maven.

# Features

This Action uses original "pom.xml", therefore can build by similar to local build environment.

# Requirement

* **pom.xml**
* **SECRET "JAVA_VERSION"**

This Action requires the "pom.xml" that was **available for the local build** to be included in the source code.
Requires Secret "JAVA_VERSION" too.

# Usage

- This Action will build in push and pull request. In any branch.
- If you want to limit branch that will build, please fix this file.

# Author

* JIN-InI

# License

This Action is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
