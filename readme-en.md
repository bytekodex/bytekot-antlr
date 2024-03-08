# Bytekot antlr

Declarations of rules for `antlr4` lexer and parser for `bytekot-painter` and other tools.

Supported:
- All opcodes, including the new Valhalla opcodes (`withfield` and `aconst_init`).
- Numbers (`decimal` & `hex`)
- String literals
- Comments
- Path to compilation file declaration
- Reference types (with full name)
- Descriptors
- Signatures
- Primitive literals (`BCLJZ`) (except `S` - challenging)
- Special types (`boolean`, `void`)
- Keywords (`public`, `private`, `protected`)
- Call types (`REF_invokeVirtual`, `REF_invokeSpecial`)
- Access flags (`ACC_SYNTHETIC`, `ACC_BRIDGE`)
- Constant pool tags (`Utf8`, `Integer`, `Methodref`)
- Package declaration

Any improvements are welcome :), https://github.com/bytekodex/bytekot-antlr/pulls