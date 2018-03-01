# Jenkins Java Template
----
## What is Jenkins?
see [Jenkins](https://jenkins.io/)
> Jenkins is an open source automation server written in Java. Jenkins helps to automate the non-human part of software development process, with continuous integration and facilitating technical aspects of continuous delivery.

## Download and run Jenkins

1. [Download Jenkins](mirrors.jenkins.io/war-stable/latest/jenkins.war).
2. Open up a terminal in the download directory.
3. Run `java -jar jenkins.war --httpPort=8080`.
4. Browse to `http://localhost:8080`.
5. Follow the instructions to complete the installation.

## Creating a simple pipeline

1. Fork this repository.
2. Click the **New Item** menu within Jenkins
3. Provide a name for your new item and select **Multibranch Pipeline**.
4. Click the **Add Source** button, choose the type of repository you want to use (github) and fill in the details. In the **Branch sources**, it's recommended to insert your github credentials, in order to avoid *rate limit exceeded* problems.
5. Click the Save button and watch the pipeline run.