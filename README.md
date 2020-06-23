# Date library for Futhark [![CI](https://github.com/diku-dk/date/workflows/CI/badge.svg)](https://github.com/diku-dk/date/actions) [![Documentation](https://futhark-lang.org/pkgs/github.com/diku-dk/date/status.svg)](https://futhark-lang.org/pkgs/github.com/diku-dk/date/latest/)

A simple date library.  Inspired by code from LexiFi.  This library
does not handle any ancient calendars or anything like that.  It's
designed for simplicity (and thereby speed).

## Installation

```
futhark pkg add github.com/diku-dk/date
futhark pkg sync
```

## Usage

```
> import "lib/github.com/diku-dk/date/date"
> check_date (1900, 2, 29)
false
> check_date (2000, 2, 29)
true
```
