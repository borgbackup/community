Resources from the Borg Community
=================================

USE AT YOUR OWN RISK!

The preferred way is that you put a link to your own repository here:

- https://github.com/sten0/btrfs-borg (script to handle btrfs-snapshots and borg)
- https://github.com/n-st/borgbench (benchmark which compression and chunking settings work best for your data and use case)
- https://github.com/mrkmg/borgbackup-zsh-completion (zsh completion for borg)
- https://github.com/obilodeau/borgbackup-scripts (cron script with xdg desktop notifications)
- https://borg.bauerj.eu/ (borg binaries for ARM/Linux)
- https://github.com/vesparny/borgjs (A node wrapper to automate and monitor backups)
- https://github.com/rear/rear (Linux bare metal disaster recovery and system migration solution with Borg as one of its backends)
- https://hub.docker.com/r/produktion/borg/ (Alpine based docker container)
- https://github.com/hkbakke/borgwrapper (Simple wrapper to make borg easier to use and configure for the generic backup use case)
- https://github.com/mxroo/borg_backupninja (Handlers and jobs for using borg with backupninja)
- https://metacpan.org/pod/distribution/App-BorgRestore/script/borg-restore.pl (restoration helper script)
- https://github.com/rugk/borg-cron-helper (Shell scripts to automate backups with additional features, such as a local lock system)
- https://github.com/matheusd/qubes-borg-rsyncnet (Script and instructions for backup strategy using Qubes OS, Borg Backup and rsync.net)
- https://github.com/anarcat/community/tree/cron.daily (simple cron job with purge and basic policies)
- https://github.com/bebehei/backup-with-borg (Simple bash wrapper managing passwords and default values)
- https://github.com/bebehei/nagios-plugin-check_borg (Icinga/Nagios check plugin to check repository archive date)
- https://github.com/milkey-mouse/backup-vm (script to make online/offline backups of libvirt-based VMs using borg)
- https://github.com/rear/rear/blob/master/doc/user-guide/04-scenarios.adoc#bootable-iso-with-borg (Relax-and-Recover scenario for borg recovery live USB)
- https://github.com/lsim/remote-borg-runner (Yet another simple shell script wrapper. Provides a template for integrating with systemd among other things)
- https://github.com/Alex131089/bbbs (Bash Borg Backup System – wrappers to handle pull-mode operation. Also comes with installer and ssh key provisioning)
- https://github.com/makeITyourway/borg_wrapper (Another Borg wrapper enables you to handle multiple projects and configs per project)
- https://github.com/engelant/borg-cygwin (Cygwin based Windows installer creator, with VSS based backup script)
- (add your link above this line)

Development
-----------
- https://github.com/Abogical/borg-gtk (A frontend for borg without the JSON API) (DISCONTINUED)

Debugging tools
---------------

- https://gist.github.com/enkore/14f7bd9f56d6cc17914a73345fd30fc4

  Shows the most commonly referenced cache entries; useful to diagnose corrupted caches.
  
- https://gist.github.com/enkore/92216e919bc0ad2602d4a429bed597fb

  Shows freeable space in a repository, mostly interesting for 1.1.x repos and --append-only repos.

- https://gist.github.com/textshell/ac8486af3fc08b52278df9c672732656

  Aggregates statistics about current and superseded objects in a repo.
