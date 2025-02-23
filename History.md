# 1.10.0 / 2019-01-21

  * JS bugfixes (#18)

# 1.9.0 / 2017-12-30

  * Add support for deployments on Google AppEngine (Thanks [mthie](https://github.com/mthie))
  * Update vendoring using `dep`

# 1.8.0 / 2017-12-24

  * Replace stdout logging with proper log package

# 1.7.0 / 2017-12-24

  * Replace insecure password hashing (Thanks [kpcyrd](https://github.com/kpcyrd) for the report)
  * Link to cloudkeys go report card

# 1.6.1 / 2017-12-08

  * Fix: Broken script URLs

# 1.6.0 / 2017-12-08

  * Update javascript libraries
  * Switch to dep for vendoring, update dependencies
  * Switch to Github publishing
  * Update Meta-Files

# 1.5.1 / 2017-02-04

  * Fix: Hide Settings menu until data has been decrypted (Thanks [rosetree](https://github.com/rosetree))

# 1.5.0 / 2017-01-22

  * Add functionality to change encryption password (Thanks [rosetree](https://github.com/rosetree))

# 1.4.1 / 2016-11-16

  * Fix small typo  in the overview template “I” → “If” (Thanks [rosetree](https://github.com/rosetree))

# 1.4.0 / 2016-05-13

  * Move to go1.6 for building
  * Migrated Godeps to go1.6 vendoring

# 1.3.1 / 2016-05-13

  * Fix: Replace not longer available libaries


1.3.0 / 2015-11-30
==================

  * Removed old clippy flash extension and replaced it with pure JS solution

1.2.4 / 2015-10-28
==================

  * Improved Dockerfile and Makefile

1.2.3 / 2015-08-25
==================

  * Replaced Google PKI certificates
  * fixed escaping for passwords with double quotes

1.2.2 / 2015-08-01
==================

  * Fix: On register the username needs to be treated like in login
  * Fixed numbering in README

1.2.1 / 2015-07-31
==================

  * Fix: Restored old behavior of making all usernames lowercase

1.2.0 / 2015-07-30
==================

  * Added documentation for Cloudcontrol and Heroku
  * Added Godeps
  * Documented ENV variables
  * Completed ENV reflection in parameters

1.1.0 / 2015-07-29
==================

  * Fixed Makefile and Dockerfile
  * Added Redis storage adapter

1.0.0 / 2015-07-29
==================

  * Initial port of CloudKeys