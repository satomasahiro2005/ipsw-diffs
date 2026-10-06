## teslad

> `/usr/libexec/teslad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe8f0` | `0xe9e8` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0xcf6` | `0xd2e` | **`+0x38`** |
| `__TEXT.__objc_stubs` | `0x26c0` | `0x26e0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2ef4` | `0x2f04` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xbc5` | `0xbd4` | **`+0xf`** |
| `__DATA.__objc_selrefs` | `0xbe8` | `0xbf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0

-  CStrings:  967
+  CStrings:  970
Functions:
~ sub_100002e38 : 548 -> 544
~ sub_1000077c8 -> sub_1000077c4 : 672 -> 668
~ sub_1000090b0 -> sub_1000090a8 : 556 -> 552
~ sub_100009b0c -> sub_100009b00 : 328 -> 332
~ sub_10000a1fc -> sub_10000a1f4 : 116 -> 236
~ sub_10000acbc -> sub_10000ad2c : 380 -> 552
~ sub_10000dd30 -> sub_10000de4c : 784 -> 780
~ sub_10000e0e0 -> sub_10000e1f8 : 380 -> 376
~ sub_10000e25c -> sub_10000e370 : 508 -> 504
~ sub_10000e66c -> sub_10000e77c : 616 -> 612
~ sub_10000e9b8 -> sub_10000eac4 : 912 -> 908
~ sub_10000edec -> sub_10000eef4 : 384 -> 380
~ sub_10000f13c -> sub_10000f240 : 388 -> 384
~ sub_10000f418 -> sub_10000f518 : 572 -> 564
CStrings:
+ "Using overridden cloud config in WithoutValidation path"
+ "_fetchOverriddenCloudConfigurationSkipValidation:completionBlock:"
+ "data"
+ "v28@0:8B16@?20"
- "_fetchOverriddenCloudConfigurationWithCompletionBlock:"
```
