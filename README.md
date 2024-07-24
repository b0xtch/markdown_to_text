# Markdown to text

### Maintained fork from https://github.com/fbecart/markdown_to_text

This Rust library converts Markdown to plain text.

## Usage

Add to your `Cargo.toml`

```toml
[dependencies]
md_to_text = '0.0.0'
```

```rust
let markdown: String = [...];
let plain_text: String = md_to_text::convert(&markdown);
```
