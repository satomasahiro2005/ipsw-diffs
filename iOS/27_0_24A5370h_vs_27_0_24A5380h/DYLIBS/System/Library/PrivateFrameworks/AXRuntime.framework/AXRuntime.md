## AXRuntime

> `/System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dd28` | `0x4df30` | **`+0x208`** |
| `__TEXT.__gcc_except_tab` | `0xb44` | `0xba4` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x5080` | `0x50a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5d53` | `0x5d6e` | **`+0x1b`** |
| `__DATA_CONST.__objc_selrefs` | `0x23f8` | `0x2408` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa90` | `0xa98` | **`+0x8`** |

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

-  Symbols:   3235
-  CStrings:  944
+  Symbols:   3236
+  CStrings:  945
Symbols:
+ _objc_terminate
Functions:
~ -[AXUIMockElement copyCachedAttributes] : 104 -> 364
~ -[AXUIElement copyCachedAttributes] : 92 -> 352
CStrings:
+ "AXUIElementCopyingElements"
```
