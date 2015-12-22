# OS X RE Tool List

This repository contains a list of handy tools for reversing on Mac OS X.
I try to upgrade this list as fast as I can. Just drop me an email if there is a handy tool that is not listed yet.

## Static Analysis

### File Inspection

* *[macholib](https://bitbucket.org/ronaldoussoren/macholib)*
>is a python library for analyzing and editing Mach-O headers.
* *[nm](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man1/nm.1.html)*
> processes (object) files and displays names/symbols.
* *[strings](https://sourceware.org/binutils/docs/binutils/strings.html)*
> searches strings in binary files.

### Disassemblers

* *[IDA](https://www.hex-rays.com/products/ida/)*
> is the state-of-the-art commercial disassembler. Scriptable, e.g. via [IDAPython](https://github.com/idapython/src).
* *[radare2](http://www.radare.org/r/)*
> is a portable reversing framework with a very strong community. Comes with disassembler, debugger, diffing tools, etc.
* *[Capstone](http://www.capstone-engine.org)*
> is a lightweight multi-platform, multi-architecture disassembly framework.

### Emulators

* *[Unicorn](http://www.unicorn-engine.org)*
>is a lightweight multi-platform, multi-architecture CPU emulator framework based on Qemu.

## Dynamic Analysis

### Debuggers

* *[LLDB](http://lldb.llvm.org)*
>is the default debugger on OS X and of course in Xcode. Scriptable, e.g. via [Python](http://lldb.llvm.org/scripting.html).
* *[dtrace](http://dtrace.org)*
>is a dynamic tracing tool that allows inspecting several aspects of a debugee. It comes with its own programming language called D.


### Hypervisors

* *[Parallels](http://www.parallels.com)*
>is a comercial hypervisor that nicely integrates into OS X. Can be used with [Vagrant](https://github.com/Parallels/vagrant-parallels) for setting up RE boxes