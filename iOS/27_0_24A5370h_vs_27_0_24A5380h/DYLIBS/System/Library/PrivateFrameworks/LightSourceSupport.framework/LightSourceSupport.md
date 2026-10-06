## LightSourceSupport

> `/System/Library/PrivateFrameworks/LightSourceSupport.framework/LightSourceSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeea8` | `0xf1d0` | **`+0x328`** |
| `__AUTH_CONST.__objc_const` | `0x3060` | `0x30b0` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x320` | `0x300` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x158` | `0x178` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x628` | `0x608` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0xb94` | `0xbac` | **`+0x18`** |
| `__TEXT.__cstring` | `0xb8c` | `0xb7b` | **`-0x11`** |
| `__DATA_CONST.__objc_selrefs` | `0x588` | `0x598` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x190` | `0x180` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x26c` | `0x274` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x424` | `0x42c` | **`+0x8`** |

### Other Changes

```diff

-8.0.58.0.0
+8.0.74.0.0

-  Functions: 457
-  Symbols:   983
-  CStrings:  230
+  Functions: 462
+  Symbols:   987
+  CStrings:  228
Symbols:
+ -[LSSCAService _integratedDisplayUsingGlobalLight]
+ -[LSSCAService displayLinkDisplayDidChangeHandler]
+ -[LSSCAService setDisplayLinkDisplayDidChangeHandler:]
+ _OBJC_IVAR_$_LSSCAService._displayLinkDisplayDidChangeHandler
+ _OBJC_IVAR_$_LSSController._providerDisplay
+ _objc_retain_x25
- ___isCalistogaEnabled_block_invoke
- __os_feature_enabled_impl
CStrings:
- "Calistoga"
- "SwiftUI"
```
