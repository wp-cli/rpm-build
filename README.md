rpm-build
=========

[![Build Status](https://travis-ci.org/wp-cli/rpm-build.svg?branch=master)](https://travis-ci.org/wp-cli/rpm-build)

Builds a RPM of the latest stable WP-CLI release using [utils/wp-cli-updaterpm.sh](https://raw.githubusercontent.com/wp-cli/wp-cli/master/utils/wp-cli-updaterpm.sh).

This is run outside the main project repo because it has a different set of environmental dependencies: `rpm rpmlint`.
