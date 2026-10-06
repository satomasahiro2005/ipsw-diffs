## NanoPassbookBridgeSettings

> `/System/Library/NanoPreferenceBundles/Applications/NanoPassbookBridgeSettings.bundle/NanoPassbookBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14a28` | `0x14998` | **`-0x90`** |
| `__TEXT.__objc_stubs` | `0x3f20` | `0x3f00` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x4b8` | `0x49c` | **`-0x1c`** |
| `__TEXT.__objc_methname` | `0x70e4` | `0x70cb` | **`-0x19`** |
| `__DATA.__objc_selrefs` | `0x1760` | `0x1758` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1329.0.0.0.0
+1334.0.0.0.0

-  CStrings:  1397
+  CStrings:  1396
Functions:
~ sub_15cc : 320 -> 352
~ sub_83c4 -> sub_83e4 : 364 -> 360
~ sub_9fdc -> sub_9ff8 : 1216 -> 1060
~ sub_a790 -> sub_a710 : 1656 -> 1644
~ sub_c358 -> sub_c2cc : 692 -> 688
CStrings:
+ "safeAreaInsets"
- "isNFCExpressEnabled"
- "isUWBExpressEnabled"
```
