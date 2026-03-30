# Contributing to NexVigilant

We welcome contributions to NexVigilant projects. This guide applies to all repositories in the organization.

## Getting Started

1. Fork the repository
2. Create a feature branch from main
3. Make your changes
4. Submit a pull request

## Quality Gates

All contributions must pass these checks before merging:

- Code formatting (fmt --check)
- Lint with zero warnings (clippy -D warnings)
- Unit tests pass (test --lib)

## Code Standards

- Rust Edition 2024 (rust-version 1.85+)
- No unwrap/expect — deny clippy unwrap_used, expect_used, panic
- No unsafe — forbid unsafe_code
- Error handling via nexcore-error + nexcore-error-derive
- Workspace dependencies defined in root Cargo.toml

## Pull Request Process

1. Write a clear summary of what changed and why
2. Reference any related issues
3. Ensure all CI checks pass
4. One approval required from a maintainer

## Reporting Issues

- Bugs: Use the bug report template
- Features: Use the feature request template
- Security vulnerabilities: See SECURITY.md for private disclosure

## License

By contributing, you agree that your contributions will be licensed under the same terms as the project (MIT OR Apache-2.0 for NexCore crates).
