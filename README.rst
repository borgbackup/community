Resources from the Borg Community
=================================

This list links to resources provided by borg users.
USE AT YOUR OWN RISK!

If you would like to have your utility or other useful resource included,
please create a pull request to add it to a suitable category below (or create
a new one if your addition doesn't fit in anywhere).

Installing borg
---------------

- https://borg.bauerj.eu/ (borg binaries for ARM/Linux)
- https://hub.docker.com/r/produktion/borg/ (Alpine based docker container)

Testing/Benchmarks
------------------

- https://github.com/n-st/borgbench (benchmark which compression and chunking settings work best for your data and use case)

Graphical front-ends
--------------------

- https://github.com/Abogical/borg-gtk (A graphical frontend for borg) (DISCONTINUED)

Shell autocompletion
--------------------

- https://github.com/mrkmg/borgbackup-zsh-completion (zsh completion for borg)

Wrappers for automation and usability
-------------------------------------

- https://github.com/sten0/btrfs-borg (script to handle btrfs-snapshots and borg)
- https://github.com/obilodeau/borgbackup-scripts (cron script with xdg desktop notifications)
- https://github.com/vesparny/borgjs (node wrapper to automate and monitor backups)
- https://github.com/rugk/borg-cron-helper (shell scripts to automate backups with additional features, such as a local lock system)
- https://github.com/anarcat/community/tree/cron.daily (simple cron job with purge and basic policies)
- https://github.com/rear/rear (Linux bare metal disaster recovery and system migration solution with Borg as one of its backends)
- https://metacpan.org/pod/distribution/App-BorgRestore/script/borg-restore.pl (restoration helper script)
- https://github.com/hkbakke/borgwrapper (Simple wrapper to make borg easier to use and configure for the generic backup use case)

Integration with external services
----------------------------------

- https://github.com/matheusd/qubes-borg-rsyncnet (Script and instructions for backup strategy using Qubes OS, Borg Backup and rsync.net)
- https://github.com/mxroo/borg_backupninja (Handlers and jobs for using borg with backupninja)

Debugging tools
---------------

- https://gist.github.com/enkore/14f7bd9f56d6cc17914a73345fd30fc4

  Shows the most commonly referenced cache entries; useful to diagnose corrupted caches.

- https://gist.github.com/enkore/92216e919bc0ad2602d4a429bed597fb

  Shows freeable space in a repository, mostly interesting for 1.1.x repos and --append-only repos.

- https://gist.github.com/textshell/ac8486af3fc08b52278df9c672732656

  Aggregates statistics about current and superseded objects in a repo.
