# Known Paths

[![License](https://img.shields.io/badge/license-Public%20Domain-blue.svg)](https://unlicense.org)
[![Compatibility](https://img.shields.io/badge/rust-1.85%2B-blue)](https://blog.rust-lang.org/2025/02/20/Rust-1.85.0/)
[![Package](https://img.shields.io/crates/v/known-paths)](https://crates.io/crates/known-paths)
[![Documentation](https://docs.rs/known-paths/badge.svg)](https://docs.rs/known-paths/)

Well-known pathnames for Rust.

## ✨ Features

- Supports opting out of any feature using comprehensive [feature flags].
- Adheres to the Rust API Guidelines in its [naming conventions].
- 100% free and unencumbered public domain software.

## 🛠️ Prerequisites

- [Rust](https://rust-lang.org) 1.85+ (2024 edition)

## ⬇️ Installation

### Installation via Cargo

```bash
cargo add known-paths
```

### Installation in `Cargo.toml` (with all features enabled)

```toml
[dependencies]
known-paths = "0.1"
```

### Installation in `Cargo.toml` (with only specific features enabled)

```toml
[dependencies]
known-paths = { version = "0.1", default-features = false, features = ["unstable"] }
```

## 👉 Examples

### Importing the library

```rust
use known_paths;
```

## 📚 Reference

https://docs.rs/known-paths/

## 👨‍💻 Development

```bash
git clone https://github.com/known-facts/known-paths.git
```

---

[![Share on X](https://img.shields.io/badge/share%20on-x-03A9F4?logo=x)](https://x.com/intent/post?url=https://github.com/known-facts/known-paths&text=Known%20Paths)
[![Share on Reddit](https://img.shields.io/badge/share%20on-reddit-red?logo=reddit)](https://reddit.com/submit?url=https://github.com/known-facts/known-paths&title=Known%20Paths)
[![Share on Hacker News](https://img.shields.io/badge/share%20on-hn-orange?logo=ycombinator)](https://news.ycombinator.com/submitlink?u=https://github.com/known-facts/known-paths&t=Known%20Paths)
[![Share on Facebook](https://img.shields.io/badge/share%20on-fb-1976D2?logo=facebook)](https://www.facebook.com/sharer/sharer.php?u=https://github.com/known-facts/known-paths)
[![Share on LinkedIn](https://img.shields.io/badge/share%20on-linkedin-3949AB?logo=linkedin)](https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/known-facts/known-paths)

[feature flags]: https://github.com/known-facts/known-paths/blob/master/lib/known-paths/Cargo.toml
[naming conventions]: https://rust-lang.github.io/api-guidelines/naming.html
