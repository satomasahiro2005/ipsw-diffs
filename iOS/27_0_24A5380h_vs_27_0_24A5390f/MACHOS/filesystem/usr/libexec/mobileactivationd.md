## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34b994` | `0x34c224` | **`+0x890`** |
| `__DATA.__data` | `0x1d38` | `0x1d58` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1c088` | `0x1c0a8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1238` | `0x1248` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 1658
-  Symbols:   4027
+  Functions: 1660
+  Symbols:   4028
Symbols:
+ _OUTLINED_FUNCTION_28
CStrings:
+ "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.0.1 built on Jul 10 2026 at 22:15:12)"
- "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.0.1 built on Jun 26 2026 at 22:45:04)"
```
