## com.apple.Safari.SearchHelper

> `/System/Library/PrivateFrameworks/SafariShared.framework/XPCServices/com.apple.Safari.SearchHelper.xpc/com.apple.Safari.SearchHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dd4` | `0x3e44` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x1d9` | `0x204` | **`+0x2b`** |
| `__TEXT.__auth_stubs` | `0x440` | `0x450` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x488` | `0x494` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x238` | **`+0x8`** |
| `__TEXT.__const` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1f0` | `0x1f8` | **`+0x8`** |

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

### Other Changes

```diff

-7625.1.22.10.3
+7625.1.24.10.1

-  Functions: 77
-  Symbols:   122
-  CStrings:  328
+  Functions: 79
+  Symbols:   123
+  CStrings:  329
Symbols:
+ __os_log_debug_impl
CStrings:
+ "Fetching suggestions using url %{private}@"
```
