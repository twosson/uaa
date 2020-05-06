# Contributing to UAA

<!-- STAET dococ generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
** Table of Contents**

- [Introduction](#introduction)
- [Contributing Code](#contributing-code)
- [Disclosing vulnerabilities](#disclosing-vulnerabilities)
- [Code Style](#code-style)
- [Pull request procedure](#pull-request-procedure)
- [Communication](#communication)
- [Conduct](#conduct)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

First: if you're unsure or afraid of anything, just ask or submit the issue or pull request anyways. You won't be
yelled at for giving it your best effort. The worst that can happen is that you'll be politely asked to change
something. We appreciate any sort of contributions, and don't want a wall of rules to get in the way of that.

## Contributing Code

## Disclosing vulnerabilities

## Code Style

Please follow these guidelines when formatting source code:

* Go code should match the output of `gofmt -s`

## Pull request procedure

To make a pull request, you will need a GitHub account; if you are unclear on this process, see GitHub's
documentation on [forking](https://help.github.com/articles/fork-a-repo) and [pull requests](https://help.github.com/articles/using-pull-requests).
Pull requests should be targeted at the `master` branch. Before creating a pull request, go through this checklist:

1. Create a feature branch off of `master` so that changes do not get mixed up.
1. [Rebase](http://git-scm.com/book/en/Git-Branching-Rebasing) your local changes against the `master` branch.
1. Run the full project test suite with the `go test ./...` (or equivalent) command and confirm that it passes.
1. Run `gofmt -s` (if the project is written in Go).
1. Ensure that each commit has a subsystem prefix (ex: `controller: `).

Pull requests will be treated as "review requests," and maintainers will give feedback on the style and substance of the patch.

Normally, all pull requests must include tests that test your change. Occasionally, a change will
be very difficult to test for. In those cases, please include a note in your commit message explaining why.

## Communication

## Conduct

Whether you are a regular contributor or a newcomer, we care about making this community a safe place for you and
we've got your back.

* We are committed to providing a friendly, safe and welcoming environment for all, regardless of gender,
    sexual orientation, disability, ethnicity, religion, or similar personal characteristic.
* Please avoid using nicknames that might detract from a friendly, safe and welcoming environment for all.
* Be kind and courteous. There is no need to be mean or rude.
* We will exclude you from interaction if you insult, demean or harass anyone. In particular, we do not tolerate
    behavior that excludes people in socially marginalized groups.
* Private harassment is also unacceptable. 
* Likewise any spamming, trolling, flaming, baiting or other attention-stealing behaviour is not welcome.

We welcome discussion about creating a welcoming, safe, and productive environment for the community. 