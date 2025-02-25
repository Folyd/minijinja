# MiniJinja Examples

This directory contains a lot of different examples that use the MiniJinja
engine.  Each example is in one directory from where you can run them with
the `cargo run` command.  Alternatively you can do `cargo run -p example-name`.

## List of Examples

* [autoreload](autoreload): shows how to use auto reloading.
* [build-script](build-script): Demonstrates how to generate Rust code with MiniJinja in build scripts.
* [debug](debug): contains an example showing the built-in `debug()` function.
* [dynamic](dynamic): demonstrates how to use dynamic objects in templates.
* [dynamic-context](dynamic-context): demonstrates how to use dynamic objects as template context.
* [error](error): shows the built-in error reporting support.
* [expr](expr): demonstrates the expression evaluation support.
* [filters](filters): Shows how to write and use custom filters and global functions.
* [generate-yaml](generate-yaml): renders YAML files from Jinja templates.
* [hello](hello): minimal Hello World example.
* [inheritance](inheritance): demonstrates how to use template inheritance.
* [load-lazy](load-lazy): Demonstrates how to load data lazy on demand.
* [load-resource](load-resource): Demonstrates how to load files dynamically from disk within templates.
* [loader](loader): shows how to load templates dynamically at runtime.
* [macros](macros): Demonstrates how to use macros and imports.
* [minimal](minimal): a Hello World example without default features.
* [recursive-for](recursive-for): demonstrates the recursive for loop.
* [render-macro](render-macro): minimal Hello World example using the `render!` macro.
* [render-template](render-template): CLI app that renders templates from string.
* [source](source): Demonstrates how to load templates from disk with the `source` feature.
* [stack-ref](stack-ref): Shows how the `minijinja-stack-ref` crate can be used to reference stack values.

## Third-party Examples

* [Actix Web Integration](https://github.com/actix/examples/blob/master/templating/minijinja)
