# embedded-storage-inmemory

An in-memory implementation of the [embedded-storage](https://github.com/rust-embedded-community/embedded-storage) traits.

`embedded-storage` defines a set of traits that can be implemented to provide non-volatile storage of different kinds, including but not limited to EEPROM, NOR-flash & NAND-flash, both external and internal.

The in-memory implementation is intended to use in unit tests or other places where you'd like to simulate a flash.

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
