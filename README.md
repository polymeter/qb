# qb: Simple, single-file helper for use with borgbackup

This is a personal attempt to unify previous borg caller scripts from a
number of different machines, with three main goals in mind:
* One script to rule them all
* Declarative configuration (well, mostly)
* Support for multiple independent backups / backup targets, e.g. daily
  backups to online storage and manually triggered backups to external HDD.
