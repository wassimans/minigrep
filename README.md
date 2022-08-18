# minigrep
 Minimal grep clone in Rust

## How to use

Search for *query* in *filename*.

```Case sensitive (with cargo run)
> cargo run better zen.txt
```

Display multiple files at once

```Case insensitive (with cargo run)
> IGNORE_CASE=1 cargo run BetTer zen.txt
```

