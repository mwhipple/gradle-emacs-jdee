gradle-emacs-jdee
===

Overview
---
A Gradle plugin to generate a `prj.el` file for use with
[JDEE](http://jdee.sourceforge.net/) in Emacs.

This will start as a copy of the code posted on
http://ignatyev-dev.blogspot.com/2013/07/gradle-projects-in-jdee.html packaged
as a proper plugin and made available on the Plugins portal, and then evolve to
follow best practices and cover new needs.

Usage
---
Right now this plugin is in its nascent stages which is just a packaged form of
the code referenced above. The plugin will add a `jdee` task to the project
which when executed will generate the `prj.el`.

For installation instructions check the
[Gradle plugin page]
(https://plugins.gradle.org/plugin/com.mattwhipple.emacs-jdee)

Disclaimer
---
I presently do not use JDEE for JVM development: instead preferring a
modified copy of malabar-mode (which I'll be releasing if it becomes generally
useful). I have plans to try JDEE again as it seems to be receiving renewed
development attention, but my time to so is very constrained.

As this plugin is in use I'll keep it clean and will work on any
issues raised, but unless I do adopt JDEE it is unlikely to acquire
unsolicited features.
