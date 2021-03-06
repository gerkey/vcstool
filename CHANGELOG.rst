^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package vcstool
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.15 (2015-09-24)
-------------------
* make version attribute in imported yaml file optional for git repos (`#19 <https://github.com/dirk-thomas/vcstool/issues/19>`_)
* if printing output fails due to encoding problems try again replacing the problematic characters
* add short option for --hide-empty, use -s and --skip-empty as synonyms (`#17 <https://github.com/dirk-thomas/vcstool/pull/17>`_)

0.1.14 (2015-05-19)
-------------------
* improve error message when executable is not available (`#16 <https://github.com/dirk-thomas/vcstool/issues/16>`_)

0.1.13 (2015-04-18)
-------------------
* use --rebase when invoking pull on import
* unify branch command behavior showing the current branch, add option --all to list all branches (`#15 <https://github.com/dirk-thomas/vcstool/issues/15>`_)

0.1.12 (2015-03-22)
-------------------
* improve output of export command in case of errors (`#13 <https://github.com/dirk-thomas/vcstool/pull/13>`_)

0.1.11 (2015-03-13)
-------------------
* fix Python 2 (regression introduced in 0.1.10)

0.1.10 (2015-03-12)
-------------------
* change license from BSD to Apache License, Version 2.0
* return code 1 if the command fails for any repository
* fix colored output to be disabled if not isatty and on Windows without ConEmuANSI

0.1.9 (2015-03-11)
------------------
* fix 'import' command for git (regression introduced in 0.1.8)

0.1.8 (2015-03-03)
------------------
* improve error message if command raises an exception
* fix 'export' command for git repositories with multiple remotes (`#11 <https://github.com/dirk-thomas/vcstool/pull/11>`_)

0.1.7 (2014-10-15)
------------------
* add '--limit-tag TAGNAME' option to 'log' command
* fix '--limit-untagged' option of 'log' command for mercurial

0.1.6 (2014-01-17)
------------------
* Python 3 compatibility
* fix '--exact' option of 'export' command for mercurial (`#6 <https://github.com/dirk-thomas/vcstool/issues/6>`_)

0.1.5 (2013-11-03)
------------------
* fix missing dependencies (`#5 <https://github.com/dirk-thomas/vcstool/issues/5>`_)

0.1.4 (2013-09-16)
------------------
* add '--hide-empty' option (`#3 <https://github.com/dirk-thomas/vcstool/issues/3>`_)
* fix 'import' command cloning to wrong path (`#4 <https://github.com/dirk-thomas/vcstool/issues/4>`_)

0.1.3 (2013-06-23)
------------------
* add 'custom' command to run arbitrary vcs commands with user-specified arguments
* add support to import entries of type 'tar' to handle arbitrary rosinstall files
* add missing completion scripts to PIP package
* update several git and hg commands to stay colorized
* fix pull command for git when repo is in a detached state

0.1.2 (2013-01-18)
------------------
* fix entrypoint of import command
* fix parsing of command output with trailing whitespaces
* fix unneccesary import of mako (`#1 <https://github.com/dirk-thomas/vcstool/issues/1>`_)

0.1.1 (2013-01-14)
------------------
* first public release
