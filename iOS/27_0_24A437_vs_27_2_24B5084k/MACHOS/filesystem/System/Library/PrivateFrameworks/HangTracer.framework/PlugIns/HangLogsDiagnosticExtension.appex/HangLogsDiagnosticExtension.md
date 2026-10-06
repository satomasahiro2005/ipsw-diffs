## HangLogsDiagnosticExtension

> `/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/HangLogsDiagnosticExtension.appex/HangLogsDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14a88` | `0x14cd4` | **`+0x24c`** |
| `__TEXT.__objc_stubs` | `0x1d20` | `0x1d80` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x2760` | `0x27a0` | **`+0x40`** |
| `__TEXT.__const` | `0x2b0` | `0x280` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x46b9` | `0x46e2` | **`+0x29`** |
| `__TEXT.__cstring` | `0x281c` | `0x283c` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xcc0` | `0xcd8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xac0` | `0xad0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x570` | `0x578` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1d8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd2c` | `0xd34` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x448` | `0x450` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x2145` | `0x2144` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-426.0.0.0.0
+430.0.0.0.0

-  Functions: 484
-  Symbols:   504
-  CStrings:  1284
+  Functions: 487
+  Symbols:   507
+  CStrings:  1289
Symbols:
+ _CFPreferencesCopyMultiple
+ ___NSDictionary0__struct
+ _defaultsTextForDomain
CStrings:
+ "%@/defaults-%@.txt"
+ "Failed to write attachment text into %@ with error: %@"
+ "UUID"
+ "allTaskingPrefNames"
+ "defaults.txt"
+ "setDisplayName:"
- "Failed to write hang history log into %@ with error: %@"
```
