## SIMSetupUIService

> `/Applications/SIMSetupUIService.app/SIMSetupUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe630` | `0xea58` | **`+0x428`** |
| `__TEXT.__objc_stubs` | `0x29c0` | `0x2a40` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x440e` | `0x447c` | **`+0x6e`** |
| `__TEXT.__cstring` | `0x14ca` | `0x152e` | **`+0x64`** |
| `__DATA_CONST.__cfstring` | `0x8a0` | `0x900` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x11f0` | `0x1210` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-968.0.0.0.0
+973.0.0.0.0

-  CStrings:  1093
+  CStrings:  1100
Functions:
~ sub_100003b7c : 12 -> 208
~ sub_100003b88 -> sub_100003c4c : 48 -> 152
~ sub_100007730 -> sub_10000785c : 988 -> 1036
~ sub_10000a844 -> sub_10000a9a0 : 12 -> 208
~ sub_10000a850 -> sub_10000aa70 : 48 -> 152
~ sub_10000b650 -> sub_10000b8d8 : 556 -> 672
~ sub_10000e1a8 -> sub_10000e4a4 : 12 -> 208
~ sub_10000e1b4 -> sub_10000e574 : 48 -> 152
CStrings:
+ "ESIMS_LOCKED_DESCRIPTION_IN_BUDDY"
+ "ESIM_LOCKED_DESCRIPTION_IN_BUDDY"
+ "SIMS_LOCKED_DESCRIPTION_IN_BUDDY"
+ "horizontalSizeClass"
+ "setNeedsUpdateOfSupportedInterfaceOrientations"
+ "traitCollection"
+ "traitCollectionDidChange:"
+ "verticalSizeClass"
- "shouldAutorotate"
```
