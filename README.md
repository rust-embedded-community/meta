# rust-embedded-community

[<img src="assets/logo/rec-logo-250x250.png" align="right" width="250">](https://github.com/rust-embedded-community/meta)

The [rust-embedded-community](https://github.com/rust-embedded-community) Github organization is simply a place for [Rust language](https://www.rust-lang.org) crates in need of a good home.

## The idea

Several members of the Rust Embedded Working Group got together at Oxidize 2019 and wondered, what can we do with these half-finished projects we've started but never quite find the time to finish? Rather than invite each other to all our repositories, we wondered if there could be a place where unloved crates could move in and get some of the care and attention they deserve. And so, the rust-embedded-community was born.

## Joining the community

We need maintainers! If you're interested in updating some of the projects we care for, open an issue on this `meta` repo, or submit a PR on this README adding yourself to the Maintainers section.

## Adding a project

We haven't really worked out any rules as to what we will and won't look after, but at the moment it's fair to say a project needs to be:

* Written in the Rust Programming Language
* Target resource constrained devices (be they small Linux devices, RTOS based or bare-metal)
* Useful to the wider Rust Embedded community (or at least, not just the author)
* Licenced under an Open Source licence

If you'd use to fork a project, open an issue and tell us about it.

## Crates.io

We're happy to be added as Owners on crates.io for projects we host. We can then help co-ordinate pushing out updates when something elsewhere in the ecosystem causes breakage. Open an issue if you want to discuss this - we might need to set up a group email account or something to avoid maintaining lots of copies of maintainer list.

## Projects

We currently look after:

* console-traits - a crate for handling text-based consoles on `no_std` embedded systems. If you implement this trait on the serial port in your project, you'll get rudimentary ANSI support for any text you print to the screen. Originally by [@thejpster](https://github.com/thejpster).

* cortex-m-scheduling - a crate for starting up multiple threads on a bare-metal Cortex-M3+ based system. Originally by [@samp20](https://github.com/samp20).

## Maintainers

* Jonathan 'theJPster' Pallant - [Github](https://github.com/thejpster) | [Twitter](https://twitter.com/therealjpster) | [Keybase](https://keybase.io/thejpster)
* James Munns - [Github](https://github.com/jamesmunns)
* Vadim Kaushan - [Github](https://github.com/disasm)
* Diego Barrios Romero - [Github](https://github.com/eldruin)

