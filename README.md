# Standard SQ-Scanner-based project analyzed on SonarCloud using Travis

[![Build status](https://travis-ci.org/SonarSource/sq-com_example_standard-sqscanner-travis.svg?branch=master)](https://travis-ci.org/SonarSource/sq-com_example_standard-sqscanner-travis) [![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=com.sonarqube.examples.standard-sqscanner-travis-project&metric=alert_status)](https://sonarcloud.io/dashboard/index/com.sonarqube.examples.standard-sqscanner-travis-project)

#### This project is analysed on [SonarCloud](https://sonarcloud.io)!

It is very easy to run an analysis on a project and push it to SonarCloud:

1. Create a `sonar-project.properties` files to store your configuration - like `sonar.projectKey` or `sonar.sources`
2. In your `.travis.yml` file:
   1. Activate the [Travis Add-on](https://docs.travis-ci.com/user/sonarcloud/)
   2. Run `sonar-scanner` at some point of time in the `script` section

You can take a look at the
[sonar-project.properties](https://github.com/SonarSource/sq-com_example_standard-sqscanner-travis/blob/master/sonar-project.properties)
and
[.travis.yml](https://github.com/SonarSource/sq-com_example_standard-sqscanner-travis/blob/master/.travis.yml)
files of this project to see it in practice.
