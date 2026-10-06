## fseventsd

> `/usr/libexec/fseventsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16ce0` | `0x16edc` | **`+0x1fc`** |
| `__TEXT.__cstring` | `0xee0` | `0xf1d` | **`+0x3d`** |
| `__TEXT.__unwind_info` | `0x360` | `0x368` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-1430.0.0.0.0
+1431.0.0.0.0

-  Functions: 392
+  Functions: 393

-  CStrings:  470
+  CStrings:  473
Symbols:
+ _basename_r
- _basename
CStrings:
+ "bname != NULL && bname_size > 0"
+ "com.apple.fseventsd.%s.%d.%s"
+ "nameForPID"
+ "system.unknown"
- "com.apple.fseventsd.%s.%d"
```
