# Rusty `.blank?`

[![Travis CI Status](https://travis-ci.org/simon0191/rusty_blank.svg?branch=master)](https://travis-ci.org/simon0191/rusty_blank)


A very simple Ruby extension that speeds up ActiveSupport's `String.blank?` method. The point of
this repository is not to distribute [another `.blank?`
speedup](https://github.com/SamSaffron/fast_blank), but to research and implement building and
distributing a Ruby + Rust extension that does not necessarily need a Rust compiler present in order
to build the Ruby extension proper.

## [Contributing](https://github.com/malept/rusty_blank/blob/master/CONTRIBUTING.md)

## Legal

This repository is copyrighted under the MIT license, unless otherwise specified.
