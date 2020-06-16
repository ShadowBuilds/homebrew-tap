ShadowBuilds homebrew-tap
=========================

This is an experimental setup, hiding in the half-light of shadows.  If you
see this paragraph, or the name ShadowBuilds, around, then this is not yet
suitable for public consumption.  <!-- FIXME: ShadowBuilds -->

## Usage

```sh
$ brew tap ShadowBuilds/tap
$ brew install ShadowBuilds/tap/nats-server
$ brew services start nats-server
```

<!--
```sh
$ brew tap nats-io/tap
$ brew install nats-io/tap/nats-server
$ brew services start nats-server
```
-->

## Why

Goals:

1. Vendor tree of installable software components relating to the NATS suite.
2. Public auditability
3. Build-options controlled to be those best suited for the project,
   configured in a way where our open source time can best help users.

Non-goals:

1. Expanding out to host software third-party both to the native ecosystem and
   to us.
2. Avoiding opinions and being flexible to any setup

