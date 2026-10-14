## mediasetupd

> `/usr/libexec/mediasetupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x6c27` | `0x6c5c` | **`+0x35`** |
| `__TEXT.__objc_methlist` | `0x1fec` | `0x1ffc` | **`+0x10`** |
| `__DATA.__objc_const` | `0x3118` | `0x3120` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1be8` | `0x1bf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  1968
+  CStrings:  1969
CStrings:
+ "homeDidSetHasOwnerAcknowledgedHomePodSiriOnboarding:"
```
