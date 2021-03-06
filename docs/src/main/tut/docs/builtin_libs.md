---
layout: docs
title: "Built-in libs"
---

## Built-in libs

These are the libraries that are currently supported:

### At the JVM

 * Java Time API (JSR-310): Package `cron4s.lib.javatime`
 * Joda Time: Package `cron4s.lib.joda`

### ScalaJS

 * JavaScript `Date` API: Package `cron4s.lib.js`
 * Java Time API (JSR-310): Package `cron4s.lib.threetenbp`. _Support is provided via [scala-java-time](https://github.com/soc/scala-java-time), which can also be used in the JVM. The two implementations for JSR-310 will be merged into one once this library reaches a final release._