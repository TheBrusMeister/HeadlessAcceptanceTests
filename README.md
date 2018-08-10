# HeadlessAcceptanceTests

### Installation Steps

* Install JDK8 - easy installation can be done via choco - https://chocolatey.org/packages/jdk8
* Install chromedriver and add to your path easy installation can be done via choco - https://chocolatey.org/packages/chromedriver
* Install Intellij
* Install the cucumber intellij plugin: how to install a plugin can be found here - https://www.jetbrains.com/help/idea/managing-plugins.html
* Right click and run the feature file in resources/features/consult_dictionary

### Summary

This is an example repo for running selenium tests headless, when the feature file is ran it will visit wikipedia search for the definition of an apple and pear and assert the definitions.

*Note*

If on a mac the java and chromedriver installation can be done via brew.