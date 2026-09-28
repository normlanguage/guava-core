# Guava 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) —— 拆分、清理并重新连接标签列表。这是通过自身的 `Module module()` 声明依赖的独立消费者程序。

在仓库根目录运行：

```sh
norm run samples/hello.norm
```

[module.norm](../guava/core/module.norm) 指定 Java 制品版本并定义公开 API。

预期输出：

```text
Norm | Java
```

API 入口：[module.norm](../guava/core/module.norm) 列出公开的 `Splitter` 和 `Joiner`。[适配器验收示例](../examples/sample/guava/core/Main.norm)覆盖更多绑定行为。
