## ospredictiond

> `/usr/libexec/ospredictiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66bb8` | `0x66d50` | **`+0x198`** |
| `__TEXT.__oslogstring` | `0x717b` | `0x71ee` | **`+0x73`** |
| `__DATA_CONST.__const` | `0x10b0` | `0x10d0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x558f` | `0x55a0` | **`+0x11`** |
| `__DATA.__bss` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x868` | `0x870` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1488` | `0x1490` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-282.0.0.0.0
+284.0.0.0.0

-  Functions: 3299
+  Functions: 3304

-  CStrings:  4763
+  CStrings:  4766
CStrings:
+ "Alarm query timed out after 5s — alarm snap disabled for this prediction query"
+ "Next alarm fire date: %{time_t}ld"
+ "inactivity.alarm"
```
