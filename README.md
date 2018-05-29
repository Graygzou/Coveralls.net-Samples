Coveralls.net Samples
=====================

These are sample configurations for using [coveralls.net](https://github.com/csMACnz/Coveralls.net) with different CI and coverage tools. Each branch is a unique scenario combination of test framework, coverage tool and coveralls.net publishing the results to [coveralls.io](https://coveralls.io/).

### [Sample Application Branch](https://github.com/csMACnz/Coveralls.net-Samples/tree/sample-application) ###
[![Appveyor Build status](https://ci.appveyor.com/api/projects/status/v4m661b28npr789g/branch/sample-application?svg=true)](https://ci.appveyor.com/project/MarkClearwater/coveralls-net-samples/branch/sample-application)
[![Build Status](https://travis-ci.org/csMACnz/Coveralls.net-Samples.svg?branch=sample-application)](https://travis-ci.org/csMACnz/Coveralls.net-Samples)

This branch represents the base application, with tests, so I can branch off of this with different build configurations and see how these are reported in different CI builds, coverage runners, and coveralls.io.

### [NUnit + monocov + Travis-CI Branch](https://github.com/csMACnz/Coveralls.net-Samples/tree/nunit-monocov-travisci) ###
[![Build Status](https://travis-ci.org/csMACnz/Coveralls.net-Samples.svg?branch=nunit-monocov-travisci)](https://travis-ci.org/csMACnz/Coveralls.net-Samples)
[![Coverage Status](https://coveralls.io/repos/csMACnz/Coveralls.net-Samples/badge.svg?branch=nunit-monocov-travisci)](https://coveralls.io/github/csMACnz/Coveralls.net-Samples?branch=nunit-monocov-travisci)

This branch uses the NUnit test runner to run the NUnit tests through monocov, and Coveralls.net is run over the results.  This branch is picked up and run by Travis-CI using the travis.yml file.
