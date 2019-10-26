# Huhi crypto utils

[![Build Status](https://travis-ci.org/huhi/crypto.svg?branch=master)](https://travis-ci.org/huhi/crypto)

Shared crypto utils for Huhi browser.

## Install

`npm install huhi-crypto`

## Docs

See [docs/api.md](docs/api.md).

Usage note: In Node.js v4 and later `Buffer` objects are backed by `Uint8Array`s,
so you can freely substitute `Buffer`s where the input specified in the docs is
`Uint8Array`. However note that the returned object will still be a `Uint8Array` unless otherwise specified in the docs.
