# Systems Administration

## Systems Administration

A single system administrator should manage all the VDEs.
Sysadmins use the same ticket/queue system as development teams.

## Virtualized Development Environments

All development environments are virtualized.
A sysadmin should configure, build and manage all of the client VDEs.
Given a high-speed network connection,
an un-configured laptop should be up and ready for work in the time it takes to brew coffee.

### Vagrant

Vagrant is a virtualized development environment that can be mass-deployed amongst developers.
Configurations can be centrally controlled,
and updates can be managed by a single person or group.

The time to deploy a new development environment should be network I/O bound.
A standard Vagrant image should be available for new developers to come onboard and immediately being working.

1. a new developer joins an existing team
2. the new dev uses vagrant to pull the latest development environment
3. the new dev pulls the repository from github
4. the new dev gets to work

Development environments should _just work_.

The same VDE should be runnable on:

1. the cloud
2. the CI server
3. the desktop / laptop

