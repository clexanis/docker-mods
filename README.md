# ACL - Docker mod for using POSIX ACL

This mod adds POSIX Access Control List to your container, to be installed/updated during container start.

In docker arguments, set an environment variable `DOCKER_MODS=clexanis/lsio-acl:dev`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=clexanis/lsio-acl:dev|linuxserver/mods:universal-git`
