Profiles
================================================================================
Profiles is a standard that allows a developer to share their personal settings
and environment across machines using a personal git repository.

## Ideas

* Create a git repository on github called "profile".  This repo will contain
  configuration files to represent your personal settings/environment.
* Dependency management will need to be done.  Say you want to use a tool like
  a C compiler, that C compiler may have dependencies on other tools.
* A user can have not just one profile but profile groups.  For example, a user
  may have a profile group for "C development" or "Java development".