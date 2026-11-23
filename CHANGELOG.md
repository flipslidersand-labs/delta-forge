# Changelog

All notable changes to this project are documented in this file.

Format: [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)
Versioning: [Semantic Versioning](https://semver.org/)

> No version has been tagged yet. The entries below summarize the git history up to the first release.

---

## [Unreleased]

### Added

- Incremental computation engine (Rust, built with Cargo) for lazy evaluation and caching strategies, delivered in implementation phases 1-6 (#2).
- Scaffold-phase README with an implementation roadmap, later made bilingual (English and Japanese).
- README now states the release type (`library`).
- MIT license.
- Continuous integration workflow (#3).
- `.gitignore` that excludes the `target/` build directory (#9).
- Committed `Cargo.lock` (#10).

### Security

- Added a gitleaks secrets scan to CI (#4).
