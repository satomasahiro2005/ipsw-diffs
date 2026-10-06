## coreauthd

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/coreauthd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38640` | `0x3878c` | **`+0x14c`** |
| `__TEXT.__const` | `0x14b8` | `0x1510` | **`+0x58`** |
| `__DATA.__data` | `0x1b90` | `0x1bb8` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x47b8` | `0x47c2` | **`+0xa`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.63.0.0
+2319.40.29.0.0

-  Functions: 1564
+  Functions: 1563
CStrings:
+ "initWithWorkQueue:deviceInfo:telemetry:"
- "initWithWorkQueue:deviceInfo:"
```
