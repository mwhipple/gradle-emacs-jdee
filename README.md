gradle-emacs-jdee
===

Overview
---

A Gradle plugin to generate a `prj.el` file for use wth [[JDEE][http://jdee.sourceforge.net/]] in Emacs.

This will start as a copy of the code posted on http://ignatyev-dev.blogspot.com/2013/07/gradle-projects-in-jdee.html packaged as a proper plugin and made available on the Plugins portal, and then evolve to follow best practices and cover new needs.

Usage
---
Right now this plugin is in its nascent stages which is just a packaged form of the code referenced above. The plugin will add a `jdee` task to the project which when executed will generate the `prj.el`.

Explicit style configuration
```groovy
buildscript {
	repositories {
		jcenter()
	}
	depenencies {
		classpath 'com.mattwhipple.gradle:gradle-emacs-jdee:+'
	}
}
```
Plugins portal integration is pending

Roadmap
---
This plugin will initially evolve to satisfy my needs as they are encountered and adhere to my preferences. The development of this plugin will also be associated with any work done on jdee itself and emacs<->JVM integration in general. PRs and issues are welcome.
