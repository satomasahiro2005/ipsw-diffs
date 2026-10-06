## BPSStingSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/BPSStingSetup.bundle/BPSStingSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x16e0` | `0x1700` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2817` | `0x2836` | **`+0x1f`** |
| `__DATA.__objc_selrefs` | `0xa20` | `0xa28` | **`+0x8`** |
| `__TEXT.__text` | `0x41f0` | `0x41f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1359.0.0.0.0
+1359.3.0.0.0

-  CStrings:  566
+  CStrings:  567
Functions:
~ sub_2494 : 1492 -> 1500
CStrings:
+ "revalidateColumnLayoutIfNeeded"
```
