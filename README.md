# Title of the projects

[![CI](https://github.com/runtime-machines/rust-template/workflows/CI/badge.svg)](https://github.com/runtime-machines/rust-template/actions)

## Description and scope of the project

Use this repository as a production ready starting point for developing bug-free, well formatted, rust projects :)

### What does this repository do:

Workflows:

- CI Workflows: 
  - Test
  - Format check
  - Clippy
  - Docs
  - Publish
  - Code coverage report on PR

- CD Workflows: \
  Release artifacts on Cargo and Github for:
  - os: macos-latest
    target: x86_64-apple-darwin
  - os: ubuntu-latest
    target: x86_64-unknown-linux-gnu
  - os: windows-latest
    target: x86_64-pc-windows-msvc
  - os: ubuntu-latest
    target: aarch64-unknown-linux-gnu
  - os: ubuntu-latest
    target: i686-unknown-linux-gnu

- Security:
  - Audit everyday at 00.00 UTC
  - dependabot to update dependencies weekly

Templates:
- Issue Templates
- Pull Request Template

## Installation

Click the "Use this template" button in the repo mainpage\
Change "rust-template" with your repository name everywhere

## License

This project license

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the license, shall be
licensed as above, without any additional terms or conditions.

See [CONTRIBUTING.md](CONTRIBUTING.md).
