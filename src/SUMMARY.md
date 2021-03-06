# Summary

[Introduction](introduction.md)

- [What are Editions?](editions/index.md)
    - [Transitioning your code to a new edition](editions/transitioning.md)

- [Rust 2015](2015/index.md)

- [Rust 2018](2018/index.md)
    - [Transitioning to Rust 2018](2018/transitioning/to-rust-2018.md)
        - [Trait system](2018/transitioning/traits/index.md)
            - [`impl Trait`](2018/transitioning/traits/impl-trait.md)
            - [`dyn Trait`](2018/transitioning/traits/dyn-trait.md)
        - [Module system](2018/transitioning/modules/index.md)
            - [Path clarity](2018/transitioning/modules/path-clarity.md)
            - [Macro changes](2018/transitioning/modules/macros.md)
        - [Concurrency additions](2018/transitioning/concurrency/index.md)
            - [`async`/`await`](2018/transitioning/concurrency/async-await.md)
        - [Ownership and lifetimes](2018/transitioning/ownership-and-lifetimes/index.md)
            - [`'_`, the anonymous lifetime](2018/transitioning/ownership-and-lifetimes/anonymous-lifetime.md)
            - [In-band lifetimes](2018/transitioning/ownership-and-lifetimes/in-band-lifetimes.md)
            - [Default match bindings](2018/transitioning/ownership-and-lifetimes/default-match-bindings.md)
            - [Lifetime elision in `impl`](2018/transitioning/ownership-and-lifetimes/lifetime-elision-in-impl.md)
            - [`T: 'a` inference in structs](2018/transitioning/ownership-and-lifetimes/struct-inference.md)
        - [Error Handling](2018/transitioning/errors/index.md)
            - [`?` in `fn main()` and `#[test]`s](2018/transitioning/errors/question-mark.md)
            - [`try`, `throw`, and `fail`](2018/transitioning/errors/try-throw-fail.md)
        - [Raw identifiers](2018/transitioning/raw-identifiers.md)
