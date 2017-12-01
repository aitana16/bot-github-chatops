<!-- [![Build Status](https://travis-ci.org/symphonyoss/bot-github-chatops.svg?branch=master)](https://travis-ci.org/symphonyoss/bot-github-chatops) -->
[![Open Issues](https://img.shields.io/github/issues/symphonyoss/bot-github-chatops.svg)](https://github.com/symphonyoss/bot-github-chatops/issues)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/symphonyoss/bot-github-chatops.svg)](http://isitmaintained.com/project/symphonyoss/bot-github-chatops "Average time to resolve an issue")
<!-- [![Dependencies Status](https://versions.deps.co/symphonyoss/bot-github-chatops/status.svg)](https://versions.deps.co/symphonyoss/bot-github-chatops) -->
[![License](https://img.shields.io/github/license/symphonyoss/bot-github-chatops.svg)](https://github.com/symphonyoss/bot-github-chatops/blob/master/LICENSE)
[![Symphony Software Foundation - Incubating](https://cdn.rawgit.com/symphonyoss/contrib-toolbox/master/images/ssf-badge-incubating.svg)](https://symphonyoss.atlassian.net/wiki/display/FM/Incubating)

# bot-github-chatops

A [Symphony](http://www.symphony.com/) bot that uses ChatOps techniques to allow a firm employee to interact in a
compliant manner with GitHub issues and PRs in the [symphonyoss GitHub organisation's
repositories](https://github.com/symphonyoss) via CLI-esque interactions with the bot.

## Current Status

Follow our progress towards an MVP [here](https://github.com/symphonyoss/bot-github-chatops/projects/1)!

## MVP Requirements

 1. Read issues / PRs - list (with some canned filtering restrictions e.g. "new", "open"), view details, etc.
 2. Comment on issue / PR
 3. Create issue

## Proposed Technologies

 * **Platform:** JVM, with Clojure as the language ([existing](https://github.com/symphonyoss/bot-unfurl) [bots](https://github.com/pmonks/bot-clj),
   [Symphony REST API binding](https://github.com/symphonyoss/clj-symphony), [GitHub API binding](https://github.com/irresponsible/tentacles/))
 * **Hosting infrastructure:** The Foundation's [OpenShift Online](https://www.openshift.com/features/index.html) instance
 * **Symphony pod:** [Foundation production pod](https://foundation.symphony.com/)

## Developer Information

[GitHub project](https://github.com/symphonyoss/bot-github-chatops)

[Bug Tracker](https://github.com/symphonyoss/bot-github-chatops/issues)

## License

Copyright © 2017 Symphony Software Foundation

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
