# Spring boot Starter
Archetype version of [Spring Initializr](https://start.spring.io/)

---
### Setup
__Clone the project:__
```shell
git clone https://github.com/abhi-13-07/springboot-starter.git
```
__Install it in local repository:__
```shell
mvn install
```
---

### Create Spring boot project
```shell
mvn archetype:generate -DarchetypeGroupId=com.github.abhi13-07 \
  -DarchetypeArtifactId=springboot-starter \ 
  -DarchetypeVersion=1.2.0 \
  -DprojectName=<projectName> \
  -DjavaVersion=<javaVersion | default 21> \
  -DspringBootVersion=<springBootVersion | default 3.5.3> \
  -DgroupId=<groupId> \
  -DartifactId=<artifactId> \
  -Dversion=<version> \
```
---
