## devicesharingd

> `/usr/libexec/devicesharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xb8` | `0xc0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-40.0.0.0.0
+40.0.1.0.0

+  - /usr/lib/swift/libswiftsimd.dylib

-  Symbols:   44
+  Symbols:   45
Symbols:
+ __swift_FORCE_LOAD_$_swiftsimd
```
