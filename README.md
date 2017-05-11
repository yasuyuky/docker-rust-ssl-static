# Docker Image for cross compilation in rust

this contains static compiled version of openssl

# Usage

```
docker run -it --rm -v ${PWD}:/source yasuyuky/rust-ssl-static cargo build --release --target=x86_64-unknown-linux-musl
```

# License

MIT
