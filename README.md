# fusedump ![License](https://img.shields.io/badge/License-GPLv2-blue.svg)
A barebones fuse dumper for the Switch, to be used with fusée gelée.

*NOTE: Your fuse dump may contain sensitive info that you probably don't want to leak.*

## Usage

 1. Build `fusedump.bin`, or grab one from our [releases](https://github.com/moriczgergo/fusedump/releases).
 2. Run fusée gelée with `fusedump.bin` instead of `fusee.bin`.

## Changes

This section is required by the original license of Atmosphere, GPLv2.

 * This originates from [ktemkin's fork of Atmosphere](https://github.com/ktemkin/Atmosphere).
 * exosphere has been stripped out, only fusee remains.
 * main.c has been modified to print the fuse data.
 * Makefile has been modified to only build fusee.

## Responsibility

**Don't blame me if you fuck up your Switch. You can't hold me responsible.**
