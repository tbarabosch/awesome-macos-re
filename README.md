# OS X RE Tool List

This repository contains a list of handy tools for reversing on Mac OS X.
I try to upgrade this list as fast as I can. Just drop me an email if there is a handy tool that is not listed yet.

## Static Analysis

### File Inspection

[macholib](https://bitbucket.org/ronaldoussoren/macholib): Python library for analyzing and editing Mach-O headers.
nm: working with object files.
strings: searching for strings in binary files.

### Hexeditors

[Hex Fiend](http://ridiculousfish.com/hexfiend/)

### Disassemblers

[IDA](https://www.hex-rays.com/products/ida/): The state-of-the-art commercial disassembler. Scriptable, e.g. via [IDAPython](https://github.com/idapython/src).
[radare2](http://www.radare.org/r/): Actually more than just a disassembler. Reversing framework with very strong community.
[Capstone](http://www.capstone-engine.org): Very strong disassembly engine.

## Dynamic Analysis

### Debuggers

[LLDB](http://lldb.llvm.org): Default debugger in Xcode. Scriptable, e.g. via [Python](http://lldb.llvm.org/scripting.html).
