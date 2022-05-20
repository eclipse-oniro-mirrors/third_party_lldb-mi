# lldb-mi

这是来自 llvm-8.0.1 的 LLDB 的机器接口驱动程序。 应用了一些补丁和 OHOS 目标修改。

# Build

lldb-mi的构建依赖于LLDB，Clang和LLVM。在已经配置了 LLDB、CLANG 和 LLVM 的系统上，可以使用以下通用方法构建 lldb-mi：

```sh
cmake . ; cmake --build .
```

