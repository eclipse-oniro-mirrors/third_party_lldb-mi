# lldb-mi

This is the LLDB's machine interface driver from llvm-8.0.1.
A few patches and OHOS target modifications are applied.

# Build

The build of lldb-mi relies on LLDB, Clang and LLVM. On a system that's already configured with LLDB, CLANG and LLVM,
the lldb-mi can be built with the following commond:

```bash
cmake . ; cmake --build .
```
