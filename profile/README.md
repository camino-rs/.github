# camino

camino is a Rust library that extends
[`std::path`](https://doc.rust-lang.org/std/path/struct.Path.html) to add new
[`Utf8PathBuf`] and
[`Utf8Path`] types.

camino is widely used within the Rust ecosystem, with over 20 million downloads from crates.io to date.

* [Repository on GitHub](https://github.com/camino-rs/camino)
* [camino on crates.io](https://crates.io/crates/camino/)
* [Documentation](https://docs.rs/camino)

## Other projects in the camino-rs organization

### camino-tempfile

camino-tempfile is a wrapper around Rust's [tempfile](https://docs.rs/tempfile/latest/tempfile/) that works with [`Utf8PathBuf`] and [`Utf8Path`].

* [Repository on GitHub](https://github.com/camino-rs/camino-tempfile)
* [camino-tempfile on crates.io](https://crates.io/crates/camino-tempfile/)
* [Documentation](https://docs.rs/camino-tempfile)

## Third-party projects that support camino

### pathdiff

[pathdiff](https://docs.rs/pathdiff) is a Rust library that performs diffs of two paths in memory. pathdiff [supports camino](https://docs.rs/pathdiff/latest/pathdiff/fn.diff_utf8_paths.html) with the optional `camino` feature.

### cap-std

[cap-std](https://docs.rs/cap-std) is a capability-based API modeled after Rust's `std`. cap-std supports camino with the optional [`fs_utf8` feature](https://docs.rs/cap-std/latest/cap_std/fs_utf8).

## Sponsorship

The primary maintainer of camino is [Rain](https://github.com/sunshowers). If you like this project, please consider [sponsoring me](https://github.com/sponsors/sunshowers)!

[`Utf8PathBuf`]: https://docs.rs/camino/latest/camino/struct.Utf8PathBuf.html
[`Utf8Path`]: https://docs.rs/camino/latest/camino/struct.Utf8Path.html
