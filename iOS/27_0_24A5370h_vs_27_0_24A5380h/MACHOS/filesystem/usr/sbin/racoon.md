## racoon

> `/usr/sbin/racoon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62eec` | `0x62f28` | **`+0x3c`** |
| `__TEXT.__cstring` | `0x56dc` | `0x56fa` | **`+0x1e`** |
| `__DATA.__bss` | `0x3300` | `0x3308` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe98` | `0xe90` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-  Functions: 2160
+  Functions: 2161

-  CStrings:  2205
+  CStrings:  2206
CStrings:
+ "bad length in yy_scan_bytes()"
```
