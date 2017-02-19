## External Maven Profile for t1 Projects

This is a [pomx](https://github.com/t1/pomx) profile for my (t1) own projects.

### Features

It mainly declares bintray, Apache license, and a few default dependencies (provided and test).
And it adds the `versions-maven-plugin` with a `rulesUri` to ignore versions in alpha, beta, etc.
See the `src/maven-versions-rules.xml` file for details.
