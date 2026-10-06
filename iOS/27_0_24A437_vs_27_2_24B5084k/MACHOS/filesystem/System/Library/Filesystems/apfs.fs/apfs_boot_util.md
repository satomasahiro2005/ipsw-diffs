## apfs_boot_util

> `/System/Library/Filesystems/apfs.fs/apfs_boot_util`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38e4` | `0x3970` | **`+0x8c`** |
| `__DATA_CONST.__cfstring` | `0x80` | `0xc0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1843` | `0x185e` | **`+0x1b`** |
| `__TEXT.__auth_stubs` | `0x5e0` | `0x5f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2f0` | `0x2f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 34
-  Symbols:   105
-  CStrings:  189
+  Functions: 35
+  Symbols:   106
+  CStrings:  191
Symbols:
+ _CFEqual
Functions:
~ sub_100003a94 : 124 -> 140
+ sub_100003b20
CStrings:
+ "IOMatchCategory"
+ "mount_apfs"
```
