## HangLogsDiagnosticExtension

> `/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/HangLogsDiagnosticExtension.appex/HangLogsDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x280` | `0x2b0` | **`+0x30`** |
| `__TEXT.__text` | `0x14a70` | `0x14a88` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xab0` | `0xac0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x568` | `0x570` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   503
+  Symbols:   504
Symbols:
+ _objc_retain_x27
Functions:
~ _checkForAssertionOverlap : 1396 -> 1392
~ sub_100006b2c -> sub_100006b28 : 7656 -> 7684
~ sub_10000b9f8 -> sub_10000ba10 : 16 -> 12
~ sub_10000ba08 -> sub_10000ba1c : 12 -> 36
~ sub_10000ba14 -> sub_10000ba40 : 36 -> 16
```
