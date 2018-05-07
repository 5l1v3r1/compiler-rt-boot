# compiler-rt for Bootstrapping

LLVM's build system effectively requires a full toolchain to build compiler-rt.

This repository contains the generic builtins component of compiler-rt with a build system that does requires no target code.
