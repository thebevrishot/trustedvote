[![Build Status](https://travis-ci.org/trustedvote/trustedvote.svg?branch=master)](https://travis-ci.org/trustedvote/trustedvote)
[![Gitter](https://badges.gitter.im/trustedvote/community.svg)](https://gitter.im/trustedvote/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# Trusted Vote

The core of Trusted Vote system. It contains libtrustedvote, which is the core of Trusted Vote, daemon and CLI for daemon.

## Build requirements

- C++17 toolchain.
- GNU Autotools.
- GNU Automake.
- GNU Libtool.

## Dependencies

- Boost 1.67

## Build instructions

```sh
./autogen.sh
```

```sh
./configure
```

```sh
make
```
