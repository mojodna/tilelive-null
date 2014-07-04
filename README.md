# tilelive-null

A noop sink for [tilelive](https://github.com/mapbox/tilelive.js).

## Usage

This provider registers `null:` as its protocol, so use that when loading your
sink.

## Why?

To allow `tilelive-http` to be used for seeding remote tile sources (without
caring about the output).
