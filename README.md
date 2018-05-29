# Semantic Versioning Caret

An extension of Semantic Versioning for initial developments.

## Specification

1. Semantic Versioning Caret (SemVer^) conforms to [Semantic Versioning 2.0.0] except for the following clauses.

2. If X (major version) is 0, versioning is *initial-development-mode*.

3. In initial-development-mode, a normal version number MUST take the form 0.X′.Y′ where X′, Y′ are non-negative integers, and MUST NOT contain leading zeroes. X′ is the *initial-major* version, and Y′ is the *initial-minor* version.

4. Initial-minor version Y′ MUST be incremented if newly backwards compatible functionality is introduced to the public API and/or backwards compatible bug fixes are introduced.

5. Initial-major version X′ MUST be incremented if any backwards incompatible changes are introduced to the public API. It MAY include initial-minor level changes. Initial-minor version MUST be reset to 0 when initial-major version is incremented.

## Author

[mosop]

## License

[Creative Commons Attribution 3.0 Unported License]

And Semantic Version Caret derives [Semantic Versioning 2.0.0], licensed by Tom Preston-Werner under [Creative Commons Attribution 3.0 Unported License].

[Creative Commons Attribution 3.0 Unported License]: http://creativecommons.org/licenses/by/3.0/
[mosop]: https://github.com/mosop
[Semantic Versioning 2.0.0]: https://semver.org/spec/v2.0.0.html
