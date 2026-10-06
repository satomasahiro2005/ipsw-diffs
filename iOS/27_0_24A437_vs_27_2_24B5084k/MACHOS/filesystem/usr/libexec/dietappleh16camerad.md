## dietappleh16camerad

> `/usr/libexec/dietappleh16camerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ae40` | `0x1b090` | **`+0x250`** |
| `__TEXT.__oslogstring` | `0x21af` | `0x223b` | **`+0x8c`** |
| `__TEXT.__auth_stubs` | `0xed0` | `0xef0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x778` | `0x788` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x538` | `0x540` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3287` | `0x3288` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`

### Other Changes

```diff

-6.21.0.0.0
+6.103.0.0.0

-  Functions: 393
-  Symbols:   289
-  CStrings:  629
+  Functions: 397
+  Symbols:   291
+  CStrings:  631
Symbols:
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
CStrings:
+ "6.103"
+ "Unexpected client Get data length=%zu expected=%zu (pid %{private}d)\n"
+ "Unexpected client Set data length=%zu expected=%zu (pid %{private}d)\n"
- "6.21"
```
