Resources from the Borg Community
=================================

This list links to resources provided by Borg users. USE AT YOUR OWN RISK!

The preferred way of extending this document is that you put a link to your own repository here:
If you would like to have your utility or other useful resource included,
please create a pull request to add it to a suitable category below
(or create a new one if your addition doesn't fit in anywhere).

Installing / Platform support
-----------------------------

- https://borg.bauerj.eu/ (Borg binaries for ARM/Linux)
- Note: Intel/AMD x64 Linux, FreeBSD, and macOS Borg binaries are available with Borg.
- https://github.com/engelant/borg-cygwin (Cygwin-based Windows installer creator with a VSS-based backup script)
- https://gitlab.com/borg-binary-builder/borg-binaries (Docker solution to build Borg binaries for various architectures)
- https://github.com/borgbase/ansible-role-borgbackup (Ansible role to set up Borg and Borgmatic for regular remote backups)
- https://github.com/adhawkins/ansible-borgbase (Ansible collection containing modules to manipulate BorgBase repositories and SSH keys)
- https://github.com/fleetwoodmac/FUSEless-Mount-macOS (Mount Borg backups on macOS without macFUSE)
- https://github.com/bbx0/container-borgbackup (Distribution of BorgBackup as a Docker image)

Graphical front-ends
--------------------

- https://github.com/borgbase/vorta/ (Vorta – desktop client for Linux and macOS)
- https://gitlab.gnome.org/World/pika-backup (Pika Backup - GTK desktop client for Linux)
- https://github.com/GaetanF/cyborgbackup (Web-based user interface, REST API, and task engine built on top of BorgBackup)
- https://salsa.debian.org/freedombox-team/freedombox/-/tree/master/plinth/modules/backups (Web-based user interface for backing up FreedomBox applications)
- https://framagit.org/framasoft/borgbackup/borg-dashboard-vue (Borg dashboard in Vue.js)
- https://borgwarehouse.com/ (A fast and modern web UI for a BorgBackup central repository server)
- https://github.com/mshopf/borg-webgui (Web-based GUI for restoring data from existing backups)
- https://apps.apple.com/app/borglens/id6743801028 (BorgLens: Securely access your Borg backup — anywhere, anytime on iPhone and iPad)
- https://github.com/mlapaglia/Borgitory (Web UI for managing BorgBackup repositories with scheduling, monitoring, and cloud sync)
- https://github.com/karanhudia/borg-ui (Borg Web UI – Modern web interface for managing BorgBackup with scheduling, real-time progress tracking, and Docker deployment)

Shell autocompletion
--------------------

- https://github.com/mrkmg/borgbackup-zsh-completion (Zsh completion for Borg)
- Note: Some shell completions are included with Borg.

Monitoring
----------

- https://github.com/bebehei/nagios-plugin-check_borg (Icinga/Nagios check plugin to check repository archive date)
- https://framagit.org/framasoft/borgbackup/borg-dashboard-exporter (Borg dashboard exporter)
- https://github.com/bbx0/borgreport (Get a report on repositories (by mail) and export metrics)

Backup tool integration
-----------------------

- https://github.com/rear/rear (Linux bare metal disaster recovery and system migration solution with Borg as one of its backends)
- https://github.com/rear/rear/blob/master/doc/user-guide/04-scenarios.adoc#bootable-iso-with-borg (Relax-and-Recover scenario for Borg recovery live USB)
- https://github.com/mxroo/borg_backupninja (Handlers and jobs for using Borg with backupninja)

Backup scripts / Borg wrappers
------------------------------

- https://github.com/witten/borgmatic (Simple wrapper script for BorgBackup that creates and prunes backups)
- https://github.com/aditosoftware/nodebackup (Collect data from config files, Docker and Kubernetes labels, and create Borg backups based on this information)
- https://github.com/sten0/btrfs-borg (Script to handle Btrfs snapshots and Borg)
- https://github.com/obilodeau/borgbackup-scripts (Cron script with XDG desktop notifications)
- https://github.com/vesparny/borgjs (A Node.js wrapper to automate and monitor backups)
- https://github.com/hkbakke/borgwrapper (Simple wrapper to make Borg easier to use and configure for the generic backup use case)
- https://metacpan.org/pod/distribution/App-BorgRestore/script/borg-restore.pl (Restoration helper script)
- https://github.com/rugk/borg-cron-helper (Shell scripts to automate backups with additional features, such as a local lock system)
- https://github.com/matheusd/qubes-borg-rsyncnet (Script and instructions for a backup strategy using Qubes OS, BorgBackup, and rsync.net)
- https://github.com/anarcat/community/tree/cron.daily (Simple cron job with purge and basic policies)
- https://github.com/bebehei/backup-with-borg (Simple Bash wrapper managing passwords and default values)
- https://github.com/milkey-mouse/backup-vm (Script to make online/offline backups of libvirt-based VMs using Borg)
- https://github.com/lsim/remote-borg-runner (Yet another simple shell script wrapper. Provides a template for integrating with systemd among other things)
- https://github.com/u1735067/bbbs (Bash Borg Backup System – wrappers to handle pull-mode operation)
- https://github.com/makeITyourway/borg_wrapper (Another Borg wrapper enables you to handle multiple projects and configs per project)
- https://bitbucket.org/pustotnik/backup-o-matic (Simple wrapper with Python configs, sending mail reports, and some other features)
- https://gitlab.com/WoJ/systemd-borg (systemd timer to launch a backup with a safe auto-generated name and prune existing backups afterward)
- https://gitlab.com/lefeverd/borgwrapper (Yet another simple wrapper script, using a YAML configuration file and cron/LaunchAgent to automate backups. Also possible to send a summary by mail)
- https://hub.docker.com/r/produktion/borg/ (Alpine-based Docker container)
- https://github.com/hagai-helman/docker-borg-server (Docker image of an SSH server with Borg support)
- https://github.com/anatsuk1/jxy-memories (JxyMemories, written in Python 3, backs up multiple logical volumes of LVM2 (Logical Volume Manager))
- https://github.com/spslater/borgapi (Python 3.9 wrapper that lets you make Borg calls from other Python scripts)
- https://github.com/YunoHost-Apps/borg_ynh/ and https://github.com/YunoHost-Apps/borgserver_ynh/ (Back up a YunoHost with Borg)
- https://codeberg.org/rpnid/snapback (SnapBack: A versatile, flexibly configurable wrapper and automation tool for BorgBackup and Snapper)
- https://github.com/mpantel/ruborg (ruborg: A friendly Ruby frontend for Borg Backup, supports per file retention policies)
- https://github.com/sebastianhaberey/easyborg (Easyborg: terminal-based comfort frontend for Borg, featuring scheduled backups and fuzzy search)

Testing / Benchmarks
--------------------

- https://github.com/n-st/borgbench (Benchmark which compression and chunking settings work best for your data and use case)

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

Some of them refer to Attic, but you can do the same stuff (and more) with BorgBackup.

- `BorgBackup Installation and Basic Usage
  <https://asciinema.org/a/28691?autoplay=1&speed=2>`_  (English screencast)

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
