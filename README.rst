Resources from the Borg Community
=================================

This list links to resources provided by borg users. USE AT YOUR OWN RISK!

The preferred way of extending this document is that you put a link to your own repository here:
If you would like to have your utility or other useful resource included,
please create a pull request to add it to a suitable category below
(or create a new one if your addition doesn't fit in anywhere).

Installing / Platform support
-----------------------------

- https://borg.bauerj.eu/ (borg binaries for ARM/Linux)
- Note: Intel/AMD x64 Linux, FreeBSD and macOS borg binaries are available with borg.
- https://github.com/engelant/borg-cygwin (Cygwin based Windows installer creator, with VSS based backup script)
- https://gitlab.com/borg-binary-builder/borg-binaries (docker solution to build borg binaries for various architectures)
- https://github.com/borgbase/ansible-role-borgbackup (Ansible role to set up Borg and Borgmatic for regular remote backups)
- https://github.com/adhawkins/ansible-borgbase (Ansible collection containing modules to manipulate Borgbase repositories and SSH keys)
- https://github.com/fleetwoodmac/FUSEless-Mount-macOS (Mount Borg backups on macOS without macFUSE)
- https://github.com/bbx0/container-borgbackup (Distribution of BorgBackup as Docker image)

Graphical front-ends
--------------------

- https://github.com/borgbase/vorta/ (Vorta – desktop client for Linux and macOS)
- https://gitlab.gnome.org/World/pika-backup (Pika Backup - GTK desktop client for Linux)
- https://github.com/GaetanF/cyborgbackup (web-based user interface, REST API and task engine built on top of BorgBackup)
- https://github.com/bpereto/borg-hive (web-based user interface for repositories and REST-API)
- https://salsa.debian.org/freedombox-team/freedombox/-/tree/master/plinth/modules/backups (Web-based user interface for backing up FreedomBox applications)
- https://framagit.org/framasoft/borgbackup/borg-dashboard-vue (borg dashboard in vuejs)
- https://borgwarehouse.com/ (A fast and modern WebUI for a BorgBackup's central repository server)
- https://github.com/mshopf/borg-webgui (Web-based GUI for restoring data from existing backups)

Shell autocompletion
--------------------

- https://github.com/mrkmg/borgbackup-zsh-completion (zsh completion for borg)
- Note: Some shell completions are included with borg.

Monitoring
----------

- https://github.com/bebehei/nagios-plugin-check_borg (Icinga/Nagios check plugin to check repository archive date)
- https://framagit.org/framasoft/borgbackup/borg-dashboard-exporter (borg dashboard exporter)
- https://github.com/bbx0/borgreport (Get a report on repositories (per mail) and export Metrics)

Backup tool integration
-----------------------

- https://github.com/rear/rear (Linux bare metal disaster recovery and system migration solution with Borg as one of its backends)
- https://github.com/rear/rear/blob/master/doc/user-guide/04-scenarios.adoc#bootable-iso-with-borg (Relax-and-Recover scenario for borg recovery live USB)
- https://github.com/mxroo/borg_backupninja (Handlers and jobs for using borg with backupninja)

Backup scripts / Borg wrappers
------------------------------

- https://github.com/witten/borgmatic (Simple wrapper script for BorgBackup that creates and prunes backups)
- https://github.com/aditosoftware/nodebackup (collect data from config files, docker and kubernetes labels and create borg backups based on this information)
- https://github.com/sten0/btrfs-borg (script to handle btrfs-snapshots and borg)
- https://github.com/obilodeau/borgbackup-scripts (cron script with xdg desktop notifications)
- https://github.com/vesparny/borgjs (A node wrapper to automate and monitor backups)
- https://github.com/hkbakke/borgwrapper (Simple wrapper to make borg easier to use and configure for the generic backup use case)
- https://metacpan.org/pod/distribution/App-BorgRestore/script/borg-restore.pl (restoration helper script)
- https://github.com/rugk/borg-cron-helper (Shell scripts to automate backups with additional features, such as a local lock system)
- https://github.com/matheusd/qubes-borg-rsyncnet (Script and instructions for backup strategy using Qubes OS, Borg Backup and rsync.net)
- https://github.com/anarcat/community/tree/cron.daily (simple cron job with purge and basic policies)
- https://github.com/bebehei/backup-with-borg (Simple bash wrapper managing passwords and default values)
- https://github.com/milkey-mouse/backup-vm (script to make online/offline backups of libvirt-based VMs using borg)
- https://github.com/lsim/remote-borg-runner (Yet another simple shell script wrapper. Provides a template for integrating with systemd among other things)
- https://github.com/u1735067/bbbs (Bash Borg Backup System – wrappers to handle pull-mode operation)
- https://github.com/makeITyourway/borg_wrapper (Another Borg wrapper enables you to handle multiple projects and configs per project)
- https://bitbucket.org/pustotnik/backup-o-matic (Simple wrapper with python configs, sending mail reports and some other features)
- https://gitlab.com/WoJ/systemd-borg (systemd timer to lauch a backup with a safe autogenerated name and prune existing backups afterwards)
- https://gitlab.com/lefeverd/borgwrapper (Yet another simple wrapper script, using a YAML configuration file and cron/LaunchAgent to automate backups. Also possible to send a summary by mail)
- https://hub.docker.com/r/produktion/borg/ (Alpine based docker container)
- https://github.com/hagai-helman/docker-borg-server (Docker image of an SSH server with Borg support)
- https://github.com/anatsuk1/jxy-memories (JxyMemories written in Python3 backups multiple logical volumes of LVM2(Logical Volume Manager))
- https://github.com/spslater/borgapi (Python3.9 wrapper that lets you make borg calls from other python scripts)
- https://github.com/YunoHost-Apps/borg_ynh/ and https://github.com/YunoHost-Apps/borgserver_ynh/ (Backup a yunohost with borg)


Testing / Benchmarks
--------------------

- https://github.com/n-st/borgbench (benchmark which compression and chunking settings work best for your data and use case)

Debugging tools
---------------

- https://gist.github.com/enkore/14f7bd9f56d6cc17914a73345fd30fc4

  Shows the most commonly referenced cache entries; useful to diagnose corrupted caches.

- https://gist.github.com/enkore/92216e919bc0ad2602d4a429bed597fb

  Shows freeable space in a repository, mostly interesting for 1.1.x repos and --append-only repos.

- https://gist.github.com/textshell/ac8486af3fc08b52278df9c672732656

  Aggregates statistics about current and superseded objects in a repo.

Videos, Talks, Presentations
----------------------------

Some of them refer to attic, but you can do the same stuff (and more) with borgbackup.

- `BorgBackup Installation and Basic Usage
  <https://asciinema.org/a/28691?autoplay=1&speed=2>`_  (english screencast)

- `TW's slides for borgbackup talks / lightning talks
  <https://slides.com/thomaswaldmann>`_ (just grab the latest ones)

- `Attic / Borg Backup talk from GPN 2015 (media.ccc.de)
  <https://media.ccc.de/browse/conferences/gpn/gpn15/gpn15-6942-attic_borg_backup.html#video>`_
- `Attic / Borg Backup talk from GPN 2015 (youtube)
  <https://www.youtube.com/watch?v=Nb5nXEKSN-k>`_

- `Attic talk from Easterhegg 2015 (media.ccc.de)
  <https://media.ccc.de/v/eh15_-_49_-__-_saal_-_201504042130_-_attic_-_the_holy_grail_of_backups_-_thomas#video>`_
- `Attic talk from Easterhegg 2015 (youtube)
  <https://www.youtube.com/watch?v=96VEAAFDtJw>`_

- `Attic Backup: Mount your encrypted backups over ssh (youtube)
  <https://www.youtube.com/watch?v=BVXDFv9YMp8>`_
