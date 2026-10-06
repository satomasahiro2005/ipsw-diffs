## HomeUIService

> `/Applications/HomeUIService.app/HomeUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x48a0` | `0x4780` | **`-0x120`** |
| `__TEXT.__cstring` | `0x9601` | `0x9551` | **`-0xb0`** |
| `__TEXT.__objc_methname` | `0x163f6` | `0x16456` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xc60` | `0xca8` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0xf6a0` | `0xf6e0` | **`+0x40`** |
| `__DATA.__objc_const` | `0xd8b8` | `0xd8e8` | **`+0x30`** |
| `__TEXT.__text` | `0x7d16c` | `0x7d19c` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x5218` | `0x5238` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x7ccc` | `0x7ce4` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1232.3.0.0.0
+1238.0.0.0.0

-  Symbols:   848
-  CStrings:  5294
+  Symbols:   857
+  CStrings:  5289
Symbols:
+ _HMAccessorySetupManagerProxAssetCategoryKey
+ _HMAccessorySetupManagerProxAssetDarkBiasKey
+ _HMAccessorySetupManagerProxAssetDarkMatrixKey
+ _HMAccessorySetupManagerProxAssetFriendlyNameKey
+ _HMAccessorySetupManagerProxAssetLightBiasKey
+ _HMAccessorySetupManagerProxAssetLightMatrixKey
+ _HMAccessorySetupManagerProxAssetPrimaryImage2xKey
+ _HMAccessorySetupManagerProxAssetPrimaryImage3xKey
+ _HMAccessorySetupManagerProxAssetVideoURLKey
Functions:
~ sub_100005ce0 : 180 -> 204
~ sub_100006124 -> sub_10000613c : 912 -> 860
~ sub_1000067d0 -> sub_1000067b4 : 296 -> 264
~ sub_10000690c -> sub_1000068d0 : 1000 -> 1036
~ sub_100006f78 -> sub_100006f60 : 496 -> 568
CStrings:
+ "grammarCheckingType"
+ "instancesRespondToSelector:"
+ "notifyProxCardLaunching"
+ "setGrammarCheckingType:"
- "HMASM.pa.category"
- "HMASM.pa.darkBias"
- "HMASM.pa.darkMatrix"
- "HMASM.pa.friendlyName"
- "HMASM.pa.lightBias"
- "HMASM.pa.lightMatrix"
- "HMASM.pa.primaryImage2x"
- "HMASM.pa.primaryImage3x"
- "HMASM.pa.videoURL"
```
