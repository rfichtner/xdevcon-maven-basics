
# xdevcon-maven-basics
This project contains the source / material related to my *maven basics and best practice* talk.

## CLI commands used the talk

### package an artifact
    mvn clean package
	
### check for plugin updates
    mvn versions:display-plugin-updates
	
### check for dependecy updates
    mvn versions:display-dependency-updates
	
### check for used / unused dependencies
	mvn dependency:analyze
	
### license report 
    mvn project-info-reports:dependencies
    mvn license:third-party-report

### security check
	mvn org.owasp:dependency-check-maven:check
	