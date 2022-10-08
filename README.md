# UEFI Semgrep Rules

Initial support to recognize some UEFI foundation concepts in source code:

- Boot services
- PEI services
- Runtime services
- Protocols
- Interesting keywords
- SMI handlers

The idea is not (yet) to find vulnerabilities, but to support manual code review by narrowing the scope to known-to-be-sensitive functionalities.

## Roadmap

- recognize NVRAM variables
- patterns for common vulnerabilities


## Related

This is inspired by [Binarly.io's FwHunt Community Scanner](https://github.com/binarly-io/fwhunt-scan).

## License

GNU General Public License v3.0
