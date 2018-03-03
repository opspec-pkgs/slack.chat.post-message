[![Build Status](https://travis-ci.org/opspec-pkgs/slack.chat.post-message.svg?branch=master)](https://travis-ci.org/opspec-pkgs/slack.chat.post-message)

<img src="icon.svg" alt="icon" height="100px">

# Problem statement

posts a message to a public, private, or direct message/IM slack channel

# Format

this version of the pkg is in [![opspec 0.1.5](https://img.shields.io/badge/opspec-0.1.5-brightgreen.svg?colorA=6b6b6b&colorB=fc16be)](https://opspec.io/0.1.5/packages.html) format

# Example usage

## Install

```shell
opctl pkg install github.com/opspec-pkgs/slack.chat.post-message#1.0.0
```

## Run

```
opctl run github.com/opspec-pkgs/slack.chat.post-message#1.0.0
```

## Compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/slack.chat.post-message#1.0.0 }
  inputs:
    msg:
    channelName:
    apiToken:
```

# Support

join us on
[![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or
[open an issue](https://github.com/opspec-pkgs/slack.chat.post-message/issues)

# Releases

releases are versioned according to
[![semver 2.0.0](https://img.shields.io/badge/semver-2.0.0-brightgreen.svg)](http://semver.org/spec/v2.0.0.html)
and [tagged](https://git-scm.com/book/en/v2/Git-Basics-Tagging); see
[CHANGELOG.md](CHANGELOG.md) for release notes

# Contributing

see
[project/CONTRIBUTING.md](https://github.com/opspec-pkgs/project/blob/master/CONTRIBUTING.md)
