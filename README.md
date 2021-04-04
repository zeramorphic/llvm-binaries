# LLVM Binaries

![Badge](https://github.com/thirdsgames/llvm-binaries/actions/workflows/compile.yml/badge.svg)

This project hosts precompiled binaries of LLVM for `x86_64-unknown-linux-gnu`, including `llvm-config` - which is notably not included in the prebuilt releases by the LLVM project. This is most useful for GitHub actions, where you don't want to wait hours for it to compile a clean copy of LLVM.

The oldest versions of LLVM (supported by `llvmenv`) are not included in this bundle due to [this bug](https://github.com/llvm-mirror/compiler-rt/commit/8a5e425a68de4d2c80ff00a97bbcb3722a4716da).
