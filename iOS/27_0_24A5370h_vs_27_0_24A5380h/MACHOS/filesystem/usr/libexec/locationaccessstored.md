## locationaccessstored

> `/usr/libexec/locationaccessstored`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x158` | `0x198` | **`+0x40`** |
| `__TEXT.__text` | `0x3794` | `0x3778` | **`-0x1c`** |
| `__TEXT.__cstring` | `0x217` | `0x232` | **`+0x1b`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b8` | `0x1b0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3169.4.0.0.0
+3176.0.0.0.0

-  Functions: 42
-  Symbols:   88
-  CStrings:  228
+  Functions: 40
+  Symbols:   89
+  CStrings:  229
Symbols:
+ _exit
CStrings:
+ "com.apple.notifyd.matching"
```
