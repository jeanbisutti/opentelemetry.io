---
title: Spring Boot starter
aliases:
  [
    /docs/languages/java/automatic/spring-boot/,
    /docs/zero-code/java/spring-boot/,
  ]
---

You can use two options to instrument Spring Boot applications with OpenTelemetry.

The default choice for instrumenting
[Spring Boot](https://spring.io/projects/spring-boot) applications is the
[*OpenTelemetry Java agent*](../agent) with byte code instrumentation:

- More out of the box instrumentation than the OpenTelemetry starter

The *OpenTelemetry Spring Boot starter* can help you with:

- *Spring Boot Native image applications* for which the OpenTelemetry Java agent
  does not work
- *Startup overhead* of the OpenTelemetry Java agent exceeding your requirements
- A Java monitoring agent already used because the OpenTelemetry Java agent might not work with the other agent
- *Spring Boot configuration files* (`application.properties`,
  `application.yml`) to configure the OpenTelemetry Spring Boot starter which
  doesn't work with the OpenTelemetry Java agent