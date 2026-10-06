## hfs.util

> `/System/Library/Filesystems/hfs.fs/hfs.util`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47e0` | `0x4a0c` | **`+0x22c`** |
| `__TEXT.__cstring` | `0x12a3` | `0x12cf` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0xd0` | `0xe8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x410` | `0x420` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x208` | `0x210` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__TEXT.__const`

### Other Changes

```diff

-753.40.3.0.0
+753.40.4.0.0

-  Functions: 28
-  Symbols:   70
-  CStrings:  127
+  Functions: 31
+  Symbols:   71
+  CStrings:  128
Symbols:
+ _warnx
CStrings:
+ "couldn't convert volume status database: %s"
```
