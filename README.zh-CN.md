# Guava

[English](README.md) | [简体中文](README.zh-CN.md)

适配声明与可运行示例位于 `guava/core`，固定 Guava 33.7.1-jre，发布坐标见 [module.norm](guava/core/module.norm)。公开面覆盖常用前置条件、字符串、拆分与连接、不可变 List/Set/Map、Multimap 和哈希 API。

独立 NAR 消费、完整 Maven 传递依赖图、无界泛型、包私有父类后的公开接口派发与 CodePoint 边界由 `GuavaBindingIntegrationTest` 验收。完整 census 与未支持原因位于 NAR 的 `binding/java-api.json`。

[可运行示例](samples/README.zh-CN.md) 展示如何作为外部 Norm 依赖使用本库。
