# Rust Lang Tutorial Road Map
### __Start a new Rust project__
`cargo new <PROJECT NAME>`

---

### __Run a project__
`cargo run`

---

### __Build a project__
`cargo build`

---

### __Run tests__
`cargo test`

---
### __Disable compiler warning for unused variables__
```rust
#![allow(unused)]
fn main() {
    //code
}
```
---

### __Install packages__
Rust packages can be found at [crates.io](https://crates.io)

To install a package, modify the `Cargo.toml` with the package and the version
```toml
<PACKAGE> = <VERSION>
# rand = "0.8.5"
```