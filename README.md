# Docker image for cross-compiling rust-lang, with static ssl library


##︎ Usage

```
docker run -it --rm -v ${PWD}:/source yasuyuky/rust-ssl-static cargo build --release --target=x86_64-unknown-linux-musl
```

## License

MIT
