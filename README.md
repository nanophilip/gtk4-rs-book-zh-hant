# The GTK-Rust Book in traditional Chinese

This is a conversion from simplified Chinese to traditional Chinese of the [Chinese translation by Chen Jingge](https://mario-hero.github.io/gtk-book-zh_cn/) of the book [*GUI development with Rust and GTK 4* by Julian Hofer](https://gtk-rs.org/gtk4-rs/stable/latest/book/). The conversion was created using the command line tool of the [Open Chinese Convert (OpenCC, 開放中文轉換)](https://github.com/BYVoid/OpenCC) project. Specifically, with the `s2t.json` [configuration](https://github.com/BYVoid/OpenCC?tab=readme-ov-file#configurations-%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6).

## Build instructions

1. Install mdbook

```bash
cargo install mdbook
```

2. Building

To view the book, execute:

```bash
mdbook serve
```

## Listings

Go to the listings folder

```bash
cd listings
```

To check if the examples build, execute:

```bash
cargo build
```

To run a specific listing, execute:

```bash
cargo run --bin listing_name
```

## License

The book itself is licensed under the [Creative Commons Attribution 3.0 Unported license](https://creativecommons.org/licenses/by/3.0/).
One exception are the code snippets which are licensed under the [MIT license](https://mit-license.org/).
The translation is licensed under the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/).
This conversion is licensed under the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/).
