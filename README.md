# Standard SQ-Scanner-based project analyzed on SonarQube.com using Travis

[![Build status](https://travis-ci.org/SonarSource/sq-com_example_standard-sqscanner-travis.svg?branch=master)](https://travis-ci.org/SonarSource/sq-com_example_standard-sqscanner-travis) [![Quality Gate](https://sonarqube.com/api/badges/gate?key=com.sonarqube.examples.standard-sqscanner-travis-project)](https://sonarqube.com/dashboard/index/com.sonarqube.examples.standard-sqscanner-travis-project)

#### This project is analysed on [SonarQube.com](https://sonarqube.com)!

It is very easy to run an analysis on a project and push it to SonarQube.com:

1. Create a `sonar-project.properties` files to store your configuration - like `sonar.projectKey` or `sonar.sources`
2. In your `.travis.yml` file:
  1. Activate the [SonarQube.com Travis Add-on](https://docs.travis-ci.com/user/sonarqube/)
  2. Run `sonar-scanner` at some point of time in the `script` section

You can take a look at the
[sonar-project.properties](https://github.com/SonarSource/sq-com_example_standard-sqscanner-travis/blob/master/sonar-project.properties)
and
[.travis.yml](https://github.com/SonarSource/sq-com_example_standard-sqscanner-travis/blob/master/.travis.yml)
files of this project to see it in practice.

### License

Copyright 2008-2016 SonarSource.

Licensed under the [GNU Lesser General Public License, Version 3.0](http://www.gnu.org/licenses/lgpl.txt)