# Islands

One crate per Island, named `rustdoit-<github>-<island>`.

1. `cargo new --lib islands/rustdoit-<github>-<island>`
2. In its `Cargo.toml` add:
   ```toml
   [dependencies]
   ap-2026-common-code.workspace = true

   [lints]
   workspace = true
   ```
3. Implement the `Island` trait from the common code.