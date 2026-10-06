## abmlite

> `/usr/bin/abmlite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c8d8` | `0x1cd44` | **`+0x46c`** |
| `__TEXT.__gcc_except_tab` | `0x20f0` | `0x214c` | **`+0x5c`** |
| `__TEXT.__auth_stubs` | `0x8c0` | `0x8f0` | **`+0x30`** |
| `__TEXT.__cstring` | `0xa59` | `0xa73` | **`+0x1a`** |
| `__DATA_CONST.__auth_got` | `0x478` | `0x490` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x568` | `0x578` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x2f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1576.0.0.0.0
+1580.0.0.0.0

-  Functions: 175
-  Symbols:   360
-  CStrings:  163
+  Functions: 176
+  Symbols:   361
+  CStrings:  165
Symbols:
+ __ZN3abm5trace33kPCIDriverSnapshotDirectorySuffixE
CStrings:
+ "PCI = "
+ "Watchdog timed out"
```
