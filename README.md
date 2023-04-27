# Projector

This is my personal implementation of the projector app, taken from the [ThePrimeagen's Polyglot programming course on Frontend Masters](https://frontendmasters.com/courses/typescript-go-rust/).

This is a cli app that functions as a fs key-value store. More details on how this app works can be found [here](https://theprimeagen.github.io/ts-go-rust/lessons/the-project/what-are-we-building).

## Key notes
- Implementations are almost identical in all three languages
- Data is retrieved from single json file stored in $HOME directory.
- All three implementations contain unit tests for core app features
## Building & running:

`$ git clone https://github.com/pavles6/projector`

### TypeScript 
```
    $ cd ./projector-ts 
    $ yarn install
    $ tsc
    $ chmod 744 dist/index.js
    $ ./dist/index.js
```
### Go
```
    $ cd ./projector-go
    $ go run cmd/projector/main.go
```

### Rust
```
    $ cargo run
```

 Note:  to pass args and/or flags to Go or Rust app you must add `--` first

