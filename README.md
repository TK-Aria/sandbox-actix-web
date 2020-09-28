# sandbox-actix-web

## test

```
$ cargo run
$ curl http://localhost:8088
```

```
$ ssh -R 80:localhost:8080 ssh.localhost.run
```

## manual install rls in docker

```
/usr/local/cargo/bin/rustup component add rust-analysis --toolchain 1.46.0-x86_64-unknown-linux-gnu
/usr/local/cargo/bin/rustup component add rust-src --toolchain 1.46.0-x86_64-unknown-linux-gnu
/usr/local/cargo/bin/rustup component add rls --toolchain 1.46.0-x86_64-unknown-linux-gnu
```
