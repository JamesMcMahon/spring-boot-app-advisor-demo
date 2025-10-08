# Spring Application Advisor Demo

This repo contains a simple outdated Spring Boot application and infrastructure to run [Spring Application Advisor](https://enterprise.spring.io/spring-application-advisor) in the pipeline.

## Setup needed for pipeline

### Repository variables

* `SPRING_COMMERCIAL_USER` - user for the broadcom commercial registry

### Secret variables

* `SPRING_COMMERCIAL_TOKEN` - token for the broadcom commercial registry
* `GIT_TOKEN_FOR_PRS` - token used to allow App Advisor to create PRs. Permissions needed: read and write for `contents` and `pull requests`.
