# Project-Pipeline2

1. Run Test Cases, Measure Code Coverage, Publish Reports:

Junit test cases are run after mvn compile. We are using the sonarQube tool to generate code coverage report. Jenkins makes a call to mvn compile which automatically executes all the test cases before measuring the code coverage. The Jenkins sonarQube plugin displays the code coverage report on the respective Jenkins Job Page.

