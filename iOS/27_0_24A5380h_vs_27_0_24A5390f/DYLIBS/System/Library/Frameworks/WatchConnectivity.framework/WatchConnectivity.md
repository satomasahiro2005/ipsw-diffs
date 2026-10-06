## WatchConnectivity

> `/System/Library/Frameworks/WatchConnectivity.framework/WatchConnectivity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2d0` | `—` | **`-0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0x3c0` | `0x690` | **`+0x2d0`** |
| `__TEXT.__text` | `0x2702c` | `0x2712c` | **`+0x100`** |
| `__DATA.__bss` | `0xb0` | `0x20` | **`-0x90`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0x110` | **`+0x90`** |
| `__TEXT.__cstring` | `0x3523` | `0x3534` | **`+0x11`** |
| `__AUTH_CONST.__auth_got` | `0x4a0` | `0x4a8` | **`+0x8`** |

### Other Changes

```diff

-223.100.4.0.0
+224.100.1.0.0

-  Functions: 924
+  Functions: 930
Symbols:
+ _CFNumberCompare
- _mallocOrAbort
CStrings:
+ "!_moa_size || _moa_result"
+ "!_roa_size || _roa_result"
- "!newSize || result"
- "!size || result"
```
