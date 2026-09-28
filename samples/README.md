# Guava samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) — Split, trim, and join a small tag list. This is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

[module.norm](../guava/core/module.norm) pins the Java artifact and defines the public API.

Expected output:

```text
Norm | Java
```

API reference: [module.norm](../guava/core/module.norm) lists the exposed `Splitter` and `Joiner`. The [adapter acceptance example](../examples/sample/guava/core/Main.norm) exercises additional binding behavior.
