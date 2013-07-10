## Pimp My Changelog

Add links to users and issues in your CHANGELOG.md.

[![Build
Status](https://travis-ci.org/pcreux/pimpmychangelog.png?branch=master)](https://travis-ci.org/pcreux/pimpmychangelog)

### Example:

> Add Travis-CI support. (@pcreux, #181)

becomes:

> Add Travis-CI support. ([@pcreux][], [#181][])
<!--- The following link definition list is generated by PimpMyChangelog --->
[#181]: https://github.com/gregbell/active_admin/issues/181
[@pcreux]: https://github.com/pcreux


### Usage:

Install:

    gem install pimpmychangelog

Go in your project directory and run:

    pimpmychangelog
      # => Your changelog is now pimped!

Notes:

* We assume the CHANGELOG file is `CHANGELOG.md`
* We assume origin points to the github repository that the issues
  belong to.
