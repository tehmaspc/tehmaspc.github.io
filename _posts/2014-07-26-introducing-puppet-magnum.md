---
layout: post
title:  "Introducing puppet-magnum"
date:   2014-07-26 13:00:00
categories: puppet-magnum puppet github
comments: true
---

I recently open sourced a tool on GitHub, [puppet-magnum][puppet-magnum], which I designed while at Pearson eCollege to make everyday Puppet module development a whole lot easier.

Some of puppet-magnum's major features are the following:

* Allows for quickly creating a working [Puppet][puppet] module directory
* Sets up [puppet-lint][puppet-lint] for lint testing
* Sets up [rspec-puppet][rspec-puppet] for unit testing
* Sets up [serverspec][serverspec] for integration testing
* Sets up a working [vagrant][vagrant] environment for testing the overall Puppet module

Check out [puppet-magnum][puppet-magnum] out for yourself on GitHub and let me know what you think!

[puppet-magnum]: https://github.com/tehmaspc/puppet-magnum
[puppet]: https://puppetlabs.com/
[puppet-lint]: http://puppet-lint.com/
[rspec-puppet]: http://rspec-puppet.com/
[Serverspec]: http://serverspec.org/
[Vagrant]: http://www.vagrantup.com/
