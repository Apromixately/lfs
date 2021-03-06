# lfs

[![CI][s3]][l3] [![MIT][s2]][l2] [![Latest Version][s1]][l1] [![Chat on Miaou][s4]][l4]

[s1]: https://img.shields.io/crates/v/lfs.svg
[l1]: https://crates.io/crates/lfs

[s2]: https://img.shields.io/badge/license-MIT-blue.svg
[l2]: LICENSE

[s3]: https://travis-ci.org/Canop/lfs.svg?branch=master
[l3]: https://travis-ci.org/Canop/lfs

[s4]: https://miaou.dystroy.org/static/shields/room.svg
[l4]: https://miaou.dystroy.org/3768?Rust


A small linux utility listing your filesystems.

It's very similar to the `df` tool you already have.

Comparison:

![comparison](doc/screenshot.png)

## Installation

Run

```
cargo install lfs
```

## Usage

```
lfs
```
By default, **lfs** doesn't show mount points with no size. Use `lfs -a` to show them all.

## Internals

If you want to display the same data in your application, have a look at the [lfs-core](https://docs.rs/lfs-core/) crate.
