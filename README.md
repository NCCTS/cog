Cog
===

<a href="https://github.com/NCCTS/cog"><img align="right" height="140" src="https://raw.githubusercontent.com/NCCTS/cog/master/support/cogs.png"></a>

[![License BSD 2-Clause](https://img.shields.io/badge/license-BSD-brightgreen.svg?style=flat)](http://opensource.org/licenses/BSD-2-Clause)
[![Build Status](https://travis-ci.org/NCCTS/cog.svg?branch=master)](https://travis-ci.org/NCCTS/cog)

> Simple and generic signaling for service availability.

Cog is envisioned for use with Docker and [Fig](http://www.fig.sh/), but could be used in other contexts as well. Cog's standalone HTTP *server* provides two "ports" &mdash; `WAIT` and `READY`; it's *cli interface* provides a means of intra and extra-container signaling via those ports (pull and/or push), so services linked between containers can startup without downstream services having to know implementation details of their service-level dependencies.

## Project Status

Cog is still on the drawing board, but active development should ramp up in January 2015.

## Copyright and License

This software is Copyright &copy; 2014 by the National Catholic Conference for Total Stewardship.<br>All rights reserved.

The use and distribution terms for this software are covered by the [BSD 2-Clause License](http://opensource.org/licenses/BSD-2-Clause) which can be found in the file [LICENSE](https://raw.githubusercontent.com/NCCTS/cog/master/LICENSE) at the [root](https://github.com/NCCTS/cog/tree/master) of this distribution. By using this software in any fashion, you are agreeing to be bound by the terms of this license. You must not remove this notice, or any other, from this software.
