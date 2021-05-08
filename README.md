* TESTS
   
    ```rust
    cargo test

* CODE COVERAGE
    
    ```rust    
    cargo install cargo-tarpaulin
    
    cargo tarpaulin --ignore-tests
    ```

* Linting
    
    ```rust
    rustup component add clippy

    cargo clippy

    cargo clippy -- -D warnings
    ```


* Formatting
    
    ```rust
    rustup component add rustfmt

    cargo fmt

    cargo fmt -- --check
    ```

* Security Vulnerabilities
    
    ```rust
    cargo install cargo-audit
    
    cargo audit
    ```

page 22 - HttpServer
page 23 - App