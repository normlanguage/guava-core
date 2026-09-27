# Guava

[English](README.md) | [简体中文](README.zh-CN.md)

The adapter declaration and runnable example are in `guava/core`. It pins Guava 33.7.1-jre and defines its package coordinates in [module.norm](guava/core/module.norm). The public API covers common preconditions, strings, splitting and joining, immutable lists/sets/maps, multimaps, and hashing.

`GuavaBindingIntegrationTest` covers standalone NAR consumption, the complete Maven transitive dependency graph, unbounded generics, dispatch through public interfaces after package-private parents, and CodePoint boundaries. The complete API census and reasons for unsupported APIs are in the NAR's `binding/java-api.json`.

[Runnable samples](samples/README.md) demonstrate the library as an external Norm dependency.
