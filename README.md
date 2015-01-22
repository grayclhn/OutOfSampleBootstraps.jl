OutOfSampleBootstraps.jl
========================

This is a Julia package that implements code for the paper "A simple
block bootstrap for asymptotically normal out-of-sample test
statistics."  (Calhoun, in progress as of Jan. 2015.) The package does
not yet offer even minimal functionality (i.e., it's not even at
version 0.1) and I strongly discourage you from using it for any
purpose other than, maybe, amusement.

My plan is to get basic versions of different bootstraps for OOS
forecast evaluation statistics working and then decide on future
directions from there.

Directory structure
-------------------

The directory structure is similar to that of most Julia packages:

* `src/` contains source code for the estimators.
* `test/` contains tests
* `perf/` contains scripts that are useful for tracking changes in
  performance over time. The scripts should be run from outside the
  package because they may check out past versions of the package.

License
-------

The OutOfSampleBootstraps.jl package is licensed under the MIT "Expat" License:

> Copyright (c) 2015: Gray Calhoun.
>
> Permission is hereby granted, free of charge, to any person obtaining
> a copy of this software and associated documentation files (the
> "Software"), to deal in the Software without restriction, including
> without limitation the rights to use, copy, modify, merge, publish,
> distribute, sublicense, and/or sell copies of the Software, and to
> permit persons to whom the Software is furnished to do so, subject to
> the following conditions:
>
> The above copyright notice and this permission notice shall be
> included in all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
> EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
> MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
> IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
> CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
> TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
> SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Build status, coverage, etc
---------------------------

* [![Build Status](https://travis-ci.org/grayclhn/OutOfSampleBootstraps.jl.svg?branch=master)](https://travis-ci.org/grayclhn/OutOfSampleBootstraps.jl)

* [![Coverage Status](https://coveralls.io/repos/grayclhn/OutOfSampleBootstraps.jl/badge.svg)](https://coveralls.io/r/grayclhn/OutOfSampleBootstraps.jl)

