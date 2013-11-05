Author: Francisco Huertas Ferrer <francisco.huertas@centeropenmiddleware.com>
Center: Center for Open Middleware, Universidad Politecnica de Madrid
License: Apache 2.0
Minimum version of puppet core 3.2

This module installs jre in a system that not has package system. Actually only has support to Debian OS family. To add support to others OS families must be create the template scripts. See template folder. 

The documentation will be update in a short time

It is necesary to ability the Experimental parser for the versio 3.2. ("parser = future" in puppet.conf for agent and master) more information [here](http://puppetlabs.com/blog/puppet-3-2-introduces-an-experimental-parser-and-new-iteration-features)
