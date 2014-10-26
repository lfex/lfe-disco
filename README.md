<img src="resources/images/ldisco.png" />


## Introduction

An LFE client library for the [Disco](https://github.com/discoproject) big-data platform.


## Dependencies

This project assumes that you have [rebar](https://github.com/rebar/rebar)
and [lfetool](https://github.com/lfe/lfetool) installed somwhere
in your ``$PATH``.


## Installation

To inlcude ``ldisco`` in your project, simply update the deps section
of your ``rebar.config``:

```erlang

    {deps, [
      {ldisco, ".*", {git, "git://github.com/thorgisl/ldisco.git"}}
    ]}
```


## Usage

TBD (project still in-progress; worker protocol will likely be the first bit
done)


## Architecture


### Initial Plan

In order to build an LFE Disco client, the following components were needed:
 * Something that can read and write the Disco worker protocol
 * Something that can read from stdout and write to stdin
 * Something that can exercise all possible workflows in the communications
   between the Disco server and the LFE Disco worker
 * Data structures representing tasks, inputs, outputs, replicas, etc.
 * Higher-level abstractions for simplifying complicated workflows


### Components

XXX


## Terms

Disco
: XXX

Disco server
: XXX

Disco worker
: XXX

Disco protocol
: XXX

Disco tasks
: XXX

ldisco
: XXX

ldisco worker
: XXX

