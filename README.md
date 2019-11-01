
# ONAP O-Parent

## Description

ONAP O-Parent provides common default settings for all the projects participating in simultaneous release.

* Isolate all the common external dependencies, default version, dependency management, plugin management, etc.
* Avoid duplicate/conflicting settings for each project
* Each project sets its parent to inherit the defaults from ONAP Parent
* Project level external dependencies and versions can be overridden if necessary

All projects participating in simultaneous release will inherit defaults from O-Parent.


elalto branch 2.X will continue to be used for Java 8/Java 9 dependencies
master branch 3.X will be used for JAva 11 dependencies

Projects should refer to either the 2.X  release Java 8/9 or 3.X release as appropriate.

