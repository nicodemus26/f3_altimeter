# `mpl3115a2`

> A platform agnostic driver to interface with the Freescale Semiconductor/NXP MPL3115A2 (barometer + altimeter + thermometer)

## What works

- Nothing

## TODO

- [ ] Get a basic barometer reading using polling
- [ ] Get a basic altimeter reading using polling
- [ ] Get a basic temperature reading using polling
- [ ] Make sure this works with the `i2cdev` crate (i.e. with the Raspberry Pi)
- [ ] Advanced configuration of the sensors
- [ ] Interrupt-mode

## Examples

There is a reference use project at
https://github.com/nicodemus26/f3_altimeter which uses this
sensor connected to an STM32F3DISCOVERY board.

## References
Datasheet https://www.nxp.com/docs/en/data-sheet/MPL3115A2.pdf

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the
work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any
additional terms or conditions.
