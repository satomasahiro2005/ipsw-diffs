## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/CoreRepairCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9af5c` | `0x9b2b8` | **`+0x35c`** |
| `__TEXT.__oslogstring` | `0xa5ad` | `0xa665` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x7668` | `0x76e8` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x4f94` | `0x4fec` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x9580` | `0x95c0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x5e0` | `0x620` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1668` | `0x1690` | **`+0x28`** |
| `__DATA.__bss` | `0x1c0` | `0x1e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x7ed4` | `0x7ef3` | **`+0x1f`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xb40` | `0xb58` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2928` | `0x2940` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1a44` | `0x1a58` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xbe0` | `0xbe8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3a4` | `0x3ac` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0xee0` | `0xee8` | **`+0x8`** |

### Other Changes

```diff

-1307.40.51.0.0
+1307.40.64.0.0

-  Functions: 2792
-  Symbols:   703
-  CStrings:  2637
+  Functions: 2805
+  Symbols:   704
+  CStrings:  2641
Symbols:
+ _NSClassFromString
CStrings:
+ "CRShipModeBatteryClient: ignoring proxyProvider seam outside a test process"
+ "CRShipModeServerNotifier: ignoring proxyProvider seam outside a test process; opening a real XPC connection"
+ "PART_CAMERA_CONTROL"
+ "XCTestCase"
```
