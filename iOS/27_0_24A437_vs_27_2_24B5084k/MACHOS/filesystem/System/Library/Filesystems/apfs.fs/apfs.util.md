## apfs.util

> `/System/Library/Filesystems/apfs.fs/apfs.util`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f58` | `0x2fe4` | **`+0x8c`** |
| `__DATA_CONST.__cfstring` | `0x20` | `0x60` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1c29` | `0x1c44` | **`+0x1b`** |
| `__TEXT.__auth_stubs` | `0x330` | `0x340` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 45
-  Symbols:   60
-  CStrings:  180
+  Functions: 46
+  Symbols:   61
+  CStrings:  182
Symbols:
+ _CFEqual
Functions:
~ sub_100001a98 : 124 -> 140
+ sub_100001b24
CStrings:
+ "IOMatchCategory"
+ "mount_apfs"
```
