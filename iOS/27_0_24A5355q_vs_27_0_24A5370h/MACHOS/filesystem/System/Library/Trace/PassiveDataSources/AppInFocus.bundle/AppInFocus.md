## AppInFocus

> `/System/Library/Trace/PassiveDataSources/AppInFocus.bundle/AppInFocus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1a6` | `0x2d5` | **`+0x12f`** |
| `__DATA_CONST.__cfstring` | `0x1c0` | `0x200` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xc8` | `0x100` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x2d3` | `0x2fe` | **`+0x2b`** |
| `__TEXT.__text` | `0xb9c` | `0xbb0` | **`+0x14`** |
| `__DATA.__objc_const` | `0x150` | `0x160` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x138` | `0x148` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-188.0.0.0.0
+196.0.0.0.0

-  Functions: 13
+  Functions: 15

-  CStrings:  66
+  CStrings:  70
CStrings:
+ "App-in-focus time series information (iOS only)"
+ "The 'AppInFocus' data source provides time series information about which application bundle ID had focus as a function of time.\nDirect application name is not available, but bundle ID, short and exact version strings, and other information is available."
+ "conciseDocumentation"
+ "detailedDocumentation"
```
