
UniMon Agent
============

[![Build Status](https://travis-ci.org/pathaugen/UniMon-Agent.svg?branch=master)](https://travis-ci.org/pathaugen/UniMon-Agent)
[![CircleCI](https://circleci.com/gh/pathaugen/UniMon-Agent.svg?style=shield)](https://circleci.com/gh/pathaugen/UniMon-Agent)
[![Build status](https://ci.appveyor.com/api/projects/status/n7354cyy4apximwb?svg=true)](https://ci.appveyor.com/project/PatrickHaugen/unimon-agent)

[![Code Climate](https://codeclimate.com/github/pathaugen/UniMon-Agent/badges/gpa.svg)](https://codeclimate.com/github/pathaugen/UniMon-Agent)
[![Test Coverage](https://codeclimate.com/github/pathaugen/UniMon-Agent/badges/coverage.svg)](https://codeclimate.com/github/pathaugen/UniMon-Agent/coverage)
[![Issue Count](https://codeclimate.com/github/pathaugen/UniMon-Agent/badges/issue_count.svg)](https://codeclimate.com/github/pathaugen/UniMon-Agent)

Agent for feeding UniMon from a single Golang binary with no dependencies.

* Code publicly hosted on GitHub: <https://github.com/pathaugen/UniMon-Agent>
* Travis CI for builds: <https://travis-ci.org/pathaugen/UniMon-Agent>
* Circle CI for builds: <https://circleci.com/gh/pathaugen/UniMon-Agent>
* AppVeyor for builds: <https://ci.appveyor.com/project/PatrickHaugen/unimon-agent>
* Code Climate: <https://codeclimate.com/github/pathaugen/UniMon-Agent>

---------- ---------- ---------- ---------- ----------

Quick Start
-----------

 * (steps to download release and launch via command line)

---------- ---------- ---------- ---------- ----------

Feature List
------------

 * Single binary with no dependencies
 * Cross platform: Windows/macOS/Linux
 * Connects to UniMon server API endpoint specified
 * Streams hardware stats to [UniMon](https://github.com/pathaugen/UniMon)

---------- ---------- ---------- ---------- ----------

External Libraries
------------------

 * **ansicolor**
   * Source: <https://github.com/shiena/ansicolor>
   * Commit included: <https://github.com/shiena/ansicolor/commit/a422bbe96644373c5753384a59d678f7d261ff10>
   * License: [MIT](https://en.wikipedia.org/wiki/MIT_License)
   * Description: Coloring of command prompt, including Windows 10.
 * **gopsutil** -> PULLED: MAJOR DEPENDENCIES WILL RESOLVE LATER VIA VENDOR
   * Source: <https://github.com/shirou/gopsutil>
   * Commit Included: <https://github.com/shirou/gopsutil/commit/77b5d0080adb6f028e457906f1944d9fcca34442>
   * License: [BSD-3-Clause](https://en.wikipedia.org/wiki/BSD_licenses#3-clause_license_.28.22Revised_BSD_License.22.2C_.22New_BSD_License.22.2C_or_.22Modified_BSD_License.22.29)
 * **go-disk-usage** -> Quick replacement until gopsutil resolved
