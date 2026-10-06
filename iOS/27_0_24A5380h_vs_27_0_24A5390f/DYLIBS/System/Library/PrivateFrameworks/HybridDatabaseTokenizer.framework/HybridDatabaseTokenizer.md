## HybridDatabaseTokenizer

> `/System/Library/PrivateFrameworks/HybridDatabaseTokenizer.framework/HybridDatabaseTokenizer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__auth_got` | `0x1a8` | `0x1d8` | **`+0x30`** |
| `__TEXT.__const` | `0x120` | `0x148` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x228` | `0x248` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xb2` | `0xd2` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x50` | `0x40` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1ac` | `0x1bc` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xa4` | `0xb4` | **`+0x10`** |
| `__TEXT.__text` | `0x2a4c` | `0x2a3c` | **`-0x10`** |
| `__DATA.__data` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x52` | `0x58` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__oslogstring` | `0x18e` | `0x18f` | **`+0x1`** |

### Other Changes

```diff

-46.0.1.0.0
+49.0.1.0.0

-  Functions: 68
-  Symbols:   66
+  Functions: 69
+  Symbols:   72
Symbols:
+ _CFRelease
+ _CFStringCreateMutableCopy
+ _CFStringNormalize
+ _CFStringTransform
+ _objc_release_x24
+ _objc_retain_x19
CStrings:
+ "HDBTokenizer: segment: sanitized input still failed UTF-8 decode (original %llu bytes)"
- "HDBTokenizer: segment: sanitized input still failed UTF-8 decode (original %zu bytes)"
```
