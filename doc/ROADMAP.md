# Roadmap

## Upcoming

### v0.0.2

Bump to v0.0.2 directly to keep in sync with libtsdb-go

- [ ] implement common compression
  - [ ] rle
  - [ ] var len
  - [ ] gorilla tgz
- [x] pick crate name, `libtsdb`, `libtsdb-rs`, `libtsdb_rs`
- [x] publish to crate

### v0.0.3

- [ ] inverted index w/p regexp support
- [ ] client protocols for what libtsdb-go already has
  - this is low priority since xephon-b will be using libtsdb-go and this only helps learning how to write http client in rust

### Future

- [ ] decode popular tsdb on disk format
  - [ ] influxdb
  - [ ] prometheus
  - [ ] graphite