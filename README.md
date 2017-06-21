
# ONAP O-Parent

## Description

ONAP O-Parent provides common default settings for all the projects participating in simultaneous release.

* Isolate all the common external dependencies, default version, dependency management, plugin management, etc.
* Avoid duplicate/conflicting settings for each project
* Each project sets its parent to inherit the defaults from ONAP Parent
* Project level external dependencies and versions can be overridden if necessary

All projects participating in simultaneous release will inherit defaults from O-Parent.

