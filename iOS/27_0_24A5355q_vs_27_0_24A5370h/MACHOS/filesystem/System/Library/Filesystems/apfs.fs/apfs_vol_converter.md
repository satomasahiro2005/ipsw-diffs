## apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/apfs_vol_converter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5937c` | `0x5a1a8` | **`+0xe2c`** |
| `__DATA.__bss` | `0x78` | `0x270` | **`+0x1f8`** |
| `__TEXT.__unwind_info` | `0xc40` | `0xcb0` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x64c` | `0x6a4` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x9f0` | `0xa10` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x500` | `0x510` | **`+0x10`** |
| `__TEXT.__cstring` | `0x11e39` | `0x11e31` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-3277.0.0.0.1
+3283.0.0.0.0

-  Functions: 887
-  Symbols:   185
+  Functions: 905
+  Symbols:   187
Symbols:
+ _pthread_create
+ _pthread_join
CStrings:
+ "3283"
- "3277.0.0.0.1"
```
