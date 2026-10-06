## assetsubscriptiond

> `/usr/libexec/assetsubscriptiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x250` | `0x240` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x130` | `0x128` | **`-0x8`** |
| `__TEXT.__text` | `0x974` | `0x970` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.61.1.0.0
+3600.67.1.0.0

-  Symbols:   63
+  Symbols:   62
Symbols:
- _objc_release_x9
Functions:
~ sub_100000da4 : 516 -> 512
```
