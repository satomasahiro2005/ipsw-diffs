## CarPlayTemplateUIHost

> `/System/Library/CoreServices/CarPlayTemplateUIHost.app/CarPlayTemplateUIHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb280` | `0xb2c8` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x3d0` | `0x410` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x2680` | `0x26a0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x35ad` | `0x35ca` | **`+0x1d`** |
| `__TEXT.__cstring` | `0x5ad` | `0x5bf` | **`+0x12`** |
| `__DATA.__objc_selrefs` | `0xd20` | `0xd28` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x300` | `0x308` | **`+0x8`** |
| `__DATA.__bss` | `0x10c` | `0x108` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-577.2.0.0.0
+580.0.0.0.0

-  Functions: 322
+  Functions: 323

-  CStrings:  800
+  CStrings:  802
CStrings:
+ "B16@?0@\"FBScene\"8"
+ "_updateRunningInCarPlayAssertionIfNecessary"
+ "bs_containsObjectPassingTest:"
- "_updateRunningInCarPlayAssertionIfNecessary:"
```
