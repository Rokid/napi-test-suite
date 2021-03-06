# NTS: N-API Test Suite

NTS is the N-API implementation conformance test suite by specfied versions and this repository
holds a copy of tests from [Node.js][] so that it can be used to validate N-API implementations
outside of [Node.js][].

## Goals

The goal of NTS is to provide the test material for those N-API implementations, which could use
NTS to assure their N-API are compatible with the specfic [Node.js][] versions.

## How to use

In this repository, we provide the 2 directories:

- [include](./include) The N-API headers contain `node_api.h` and `node_api_types.h`, the
  test suite depends on these headers to build.
- [src](./src) The test suite source directory.
  - [src/README.md](./src/README.md) This README tells you what's the current version of NTS.
  - [src/addons-napi](./src/addons-napi) The source directory of the N-API tests from [Node.js][].

## How to run

> This is still work in progress

Development of NTS is an on-going process, for now we only provide the source for the test suite and N-API implementors will need to figure out how to use to test in their environment. We are open to adding new directories/files (including potentially those specific to a particular implementer) to make that process easier.

## NTS Runners

> If you are the N-API implmentor, please fill this section.

[Node.js]: https://github.com/nodejs/node
