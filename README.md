# Cryptovec

Unswappable byte vectors that get cleared on `drop` (the Rust equivalent of `free`). On resize (`realloc`), the former version also gets cleared.

This is used for example to hold keys and sessions in [Thrussh](//nest.pijul.com/pijul_org/thrussh).

## Contributing

We welcome contributions.

By contributing, you agree to license all your contributions under the Apache 2.0 license.

Moreover, the main platform for contributing is [the Nest](//nest.pijul.com/pijul_org/cryptovec), which is still at an experimental stage. Therefore, even though we do our best to avoid it, our repository might be reset, causing the patches of all contributors to be merged.
