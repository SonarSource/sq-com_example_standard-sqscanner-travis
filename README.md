# Java Maven-based project analyzed on SonarQube.com using Travis

[![Build status](https://travis-ci.org/SonarSource/sq-com_example_java-maven-travis.svg?branch=master)](https://travis-ci.org/SonarSource/sq-com_example_java-maven-travis) [![Quality Gate](https://sonarqube.com/api/badges/gate?key=com.sonarqube.examples:java-maven-travis-project)](https://sonarqube.com/dashboard/index/com.sonarqube.examples:java-maven-travis-project)

#### This project is analysed on [SonarQube.com](https://sonarqube.com)!

It is very easy to run an analysis on a Maven-based project and push it to SonarQube.com.
You simply have to do 2 things in your `.travis.yml` file:
* Activate the [SonarQube.com Travis Add-on](https://docs.travis-ci.com/user/sonarqube/)
* Run `mvn sonar:sonar` at some point of time in the `script` section

You can take a look at the [.travis.yml file](https://github.com/SonarSource/sq-com_example_java-maven-travis/blob/master/.travis.yml) 
of this project to see it in practice.
