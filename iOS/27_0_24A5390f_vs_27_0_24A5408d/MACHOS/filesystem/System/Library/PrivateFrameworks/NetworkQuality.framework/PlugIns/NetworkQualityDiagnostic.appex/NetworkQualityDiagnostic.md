## NetworkQualityDiagnostic

> `/System/Library/PrivateFrameworks/NetworkQuality.framework/PlugIns/NetworkQualityDiagnostic.appex/NetworkQualityDiagnostic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45cc` | `0x4668` | **`+0x9c`** |
| `__DATA_CONST.__cfstring` | `0x1100` | `0x1160` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xd80` | `0xdc0` | **`+0x40`** |
| `__TEXT.__cstring` | `0xa17` | `0xa48` | **`+0x31`** |
| `__TEXT.__objc_methname` | `0x785` | `0x7a7` | **`+0x22`** |
| `__DATA.__objc_selrefs` | `0x368` | `0x378` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-220.0.0.0.0
+224.0.0.0.0

-  Symbols:   82
-  CStrings:  260
+  Symbols:   83
+  CStrings:  265
Symbols:
+ ___NSArray0__struct
Functions:
~ sub_100000dd4 : 8256 -> 8300
~ sub_1000036e0 -> sub_10000370c : 4848 -> 4960
CStrings:
+ "   Draft Version: %ld\n"
+ "cli_options"
+ "commandLineArguments"
+ "draftVersion"
+ "draft_version"
```
