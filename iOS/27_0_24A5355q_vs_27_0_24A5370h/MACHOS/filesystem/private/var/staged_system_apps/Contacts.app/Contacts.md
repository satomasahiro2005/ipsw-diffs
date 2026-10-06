## Contacts

> `/private/var/staged_system_apps/Contacts.app/Contacts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf6fc` | `0xf778` | **`+0x7c`** |
| `__TEXT.__objc_methname` | `0x5e97` | `0x5ec5` | **`+0x2e`** |
| `__TEXT.__objc_stubs` | `0x3e20` | `0x3e40` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x15f8` | `0x1608` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1df8` | `0x1e08` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x578` | `0x580` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1450.100.6.0.0
+1452.100.5.0.0

-  Functions: 515
+  Functions: 516

-  CStrings:  1154
+  CStrings:  1156
CStrings:
+ "setTraitCollection:"
+ "traitCollectionDidChange:"
```
