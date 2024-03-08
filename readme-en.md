# Bytekot antlr

Declarations of rules for `antlr4` lexer and parser for `bytekot-painter` and other tools.

## Supports:

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

## Build

### Requirements

- JDK (or JRE) 11 version or higher.

### Steps

1. We'll generate the antlr lexer and parser

Build artifacts will located in `/src/antlr`

```shell
java -jar <antlr jar> JBytecodeParser.g4 JBytecodeLexer.g4 -o /src/antlr/
```

## Improvements and bug fixes

Any improvements are welcome :), https://github.com/bytekodex/bytekot-antlr/pulls