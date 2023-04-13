# Parse hyperlinks

[nom_take_until_unbalanced](https://crates.io/crates/nom_take_until_unbalanced),
a parser library written with [Nom](https://crates.io/crates/nom) to
recognize hyperlinks and link reference definitions in Markdown,
reStructuredText, Asciidoc and HTML formatted text input.

[![Cargo](https://img.shields.io/crates/v/nom_take_until_unbalanced.svg)](
https://crates.io/crates/nom_take_until_unbalanced)
[![Documentation](https://docs.rs/nom_take_until_unbalanced/badge.svg)](
https://docs.rs/nom_take_until_unbalanced)
[![License](https://img.shields.io/badge/license-MIT%2FApache--2.0-blue.svg)](
https://gitlab.com/getreu/nom_take_until_unbalanced)

To illustrate the usage and the
[API of the library](https://docs.rs/nom_take_until_unbalanced/0.19.6/parse_hyperlinks/index.html),
[Parse-hyperlinks](https://crates.io/crates/nom_take_until_unbalanced) comes with a
simple command line application:
[Atext2html](https://crates.io/crates/atext2html)

This work is extracted from [parse-hyperlinks](https://crates.io/crates/parse-hyperlinks) by Jems Getreu and extended to fix bugs.
The authors of this crate have no affiliation to the Nom team and its name only reflects that it's meant to use as an extension for it.
