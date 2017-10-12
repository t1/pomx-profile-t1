## External Maven Profile for t1 Projects

This is a [pomx](https://github.com/t1/pomx) profile for my (t1) own projects.

### Features

* A few default dependencies (provided and test).
* The `maven-war-plugin` to include the version, etc. into the manifest and not include the maven files.
* The `maven-failsafe-plugin` to run integration tests.
* The `versions-maven-plugin` with a `rulesUri` to ignore versions in alpha, beta, etc.
See the `src/maven-versions-rules.xml` file for details.
* bintray
* Apache license
