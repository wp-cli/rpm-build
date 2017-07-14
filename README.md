rpm-build
=========

[![Build Status](https://travis-ci.org/wp-cli/rpm-build.svg?branch=master)](https://travis-ci.org/wp-cli/rpm-build)

Builds a RPM of the latest stable WP-CLI release using [utils/wp-cli-updaterpm.sh](https://raw.githubusercontent.com/wp-cli/wp-cli/master/utils/wp-cli-updaterpm.sh).

To generate a new RPM build, trigger a Travis build on the repo (either by restarting an existing build or making some non-functional change).

This is run outside the main project repo because it has a different set of environmental dependencies: `rpm rpmlint`
