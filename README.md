# java-cli-maven-surefire-pmd-allure-cucumber-testng-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using testng
and cucumber framework with
pmd, allure, and surefire plugins.

Serves allure report from link given
after the build.

## Tech stack
- java
- maven
  - testng
  - surefire
  - cucumber
  - pmd
	- allure

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
