# Hack

## Publish

- https://doc.rust-lang.org/cargo/reference/publishing.html
- https://github.com/hyperium/hyper/blob/master/Cargo.toml is a good example of what should be put into Cargo.toml

```bash
cargo package --list
cargo publish --dry-run
cargo publish
```