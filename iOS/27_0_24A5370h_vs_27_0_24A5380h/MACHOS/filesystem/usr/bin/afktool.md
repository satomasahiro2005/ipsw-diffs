## afktool

> `/usr/bin/afktool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e24` | `0x8390` | **`+0x56c`** |
| `__TEXT.__gcc_except_tab` | `0xf18` | `0x1004` | **`+0xec`** |
| `__DATA_CONST.__objc_dictobj` | `0xa0` | `0x28` | **`-0x78`** |
| `__TEXT.__cstring` | `0xf47` | `0xf9f` | **`+0x58`** |
| `__DATA_CONST.__objc_arraydata` | `0x60` | `0x10` | **`-0x50`** |
| `__DATA_CONST.__cfstring` | `0xa40` | `0xa80` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x800` | `0x7f0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x410` | `0x408` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x328` | `0x330` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`

### Other Changes

```diff

-743.0.0.0.1
+743.0.2.0.0

-  Functions: 85
-  Symbols:   177
-  CStrings:  230
+  Functions: 86
+  Symbols:   176
+  CStrings:  233
Symbols:
- _objc_retain_x23
CStrings:
+ "--service-matching"
+ "AppleFirmwareKit ToolvRC_ProjectBuildVersion Jun 29 2026 21:19:36"
+ "ERROR! Could not parse --service-matching value"
+ "Service matching: %@"
- "AppleFirmwareKit ToolvRC_ProjectBuildVersion Jun 16 2026 00:00:47"
```
