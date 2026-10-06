## mount_tmpfs

> `/System/Library/Filesystems/tmpfs.fs/mount_tmpfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x520` | `0x568` | **`+0x48`** |
| `__TEXT.__cstring` | `0x250` | `0x279` | **`+0x29`** |
| `__TEXT.__auth_stubs` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x88` | `0x90` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-92.0.0.0.0
+93.0.0.0.0

-  Symbols:   25
-  CStrings:  33
+  Symbols:   26
+  CStrings:  34
Symbols:
+ _strcmp
Functions:
~ sub_100000570 : 1240 -> 1312
CStrings:
+ "unexpected special device: %s\n"
+ "usage: mount_tmpfs [-o options] [-i | -e] [-n max_nodes] [-s max_mem_size] [special] <directory>"
- "usage: mount_tmpfs [-o options] [-i | -e] [-n max_nodes] [-s max_mem_size] <directory>"
```
