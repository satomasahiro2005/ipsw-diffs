## AppSSODaemon

> `/System/Library/PrivateFrameworks/AppSSO.framework/Support/AppSSODaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e54` | `0x7f20` | **`+0xcc`** |
| `__TEXT.__gcc_except_tab` | `0x14c` | `0x170` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x14a0` | `0x1480` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x164f` | `0x1630` | **`-0x1f`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x2b0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x690` | `0x688` | **`-0x8`** |
| `__TEXT.__const` | `0xc0` | `0xc8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-635.0.0.0.0
+643.0.12.0.0

-  Functions: 177
+  Functions: 179

-  CStrings:  446
+  CStrings:  445
Symbols:
+ _objc_retain_x26
- _objc_retain_x27
CStrings:
- "auditTokenFromData:auditToken:"
```
