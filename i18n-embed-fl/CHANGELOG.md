# Changelog for `i18n-embed-fl`

## v0.1.2

+ Change the `loader` argument to be an expression, instead of an ident, so it allows more use cases.

## v0.1.1

+ Remove `proc_macro_diagnostic` feature causing problems compiling on stable, and use `proc-macro-error` crate instead.

## v0.1.0

+ Initial version, introduces the `fl!()` macro.