### What is Git

Version Control
* System stored all versions (all historical status) for each files over time.
* Normally software source code (text) file, OK with binary file.
* All the operations with version
   * Recall to specific version
   * Recall to specific time
   * Compare the difference between two versions / over time
   * Revert file/project to previous states
   * Who modified that version that causing that difference

Centralized Version Control Systems
* CVS, CVS, Subversion, and Perforce etc.
* Single server (tranditional) - single point of failure as well

Distributed Version Control Systems
* Client fully mirror the repository, including its full history
* Git, Mercurial, Bazaar or Darcs

Git
* Linus Torvalds, the creator of Linux, and the Linux development community created for Linux kernel open source software project in 2005.
* Goals: Speed, Simple, Parallel branches, Fully distributed, Large in data size as well
* Snapshots, not differences
* Nearly Every Operation Is Local
* Everything in Git is checksummed with SHA-1 hash - Integrity
* Generally Only Adds Data - everything can undo
* States: modified, staged, and committed. Pushed to remote central point

Installing Git
* Ubuntu
   * sudo apt install git-all
* Mac OS X, Windows
   * Download from https://git-scm.com/downloads
* GUI Clients - https://git-scm.com/downloads/guis
* Installing from source
   * sudo apt-get install dh-autoreconf libcurl4-gnutls-dev libexpat1-dev gettext libz-dev libssl-dev
   * sudo apt-get install asciidoc xmlto docbook2x install-info
   * https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.24.1.tar.gz from https://mirrors.edge.kernel.org/pub/software/scm/git/
   * tar -zxf git-2.8.0.tar.gz && cd git-2.8.0 && make configure && ./configure --prefix=/usr && make all doc info && sudo make install install-doc install-html install-info
