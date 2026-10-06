## RemoteManagementUI

> `/System/Library/PrivateFrameworks/RemoteManagementUI.framework/RemoteManagementUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7900` | `0x7734` | **`-0x1cc`** |
| `__DATA_CONST.__const` | `0x338` | `0x310` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x700` | `0x6d8` | **`-0x28`** |
| `__TEXT.__oslogstring` | `0x67e` | `0x65d` | **`-0x21`** |
| `__AUTH_CONST.__cfstring` | `0x8c0` | `0x8a0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x190` | `0x188` | **`-0x8`** |
| `__TEXT.__cstring` | `0x817` | `0x80f` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2b8` | **`+0x8`** |

### Other Changes

```diff

-624.0.10.0.0
+624.2.3.0.0

-  Functions: 292
-  Symbols:   604
-  CStrings:  117
+  Functions: 291
+  Symbols:   601
+  CStrings:  115
Symbols:
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e28_v24?0"NSData"8"NSError"16ls32l8s72l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e44_v24?0"RMModelDeclarationBase"8"NSError"16ls32l8s80l8s40l8s48l8s56l8s64l8s72l8
- _NSTemporaryDirectory
- _OBJC_CLASS_$_NSFileManager
- ___block_descriptor_56_e8_32s40s48bs_e30_v24?0"NSString"8"NSError"16ls32l8s40l8s48l8
- ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e20_v20?0B8"NSError"12ls32l8s40l8s80l8s48l8s56l8s64l8s72l8
- ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e44_v24?0"RMModelDeclarationBase"8"NSError"16ls32l8s40l8s80l8s48l8s56l8s64l8s72l8
CStrings:
+ "Error resolving asset for declaration %{public}@: %{public}@"
+ "v24@?0@\"NSData\"8@\"NSError\"16"
- "%@.mobileconfig"
- "Download asset URL: %{public}@"
- "Error downloading asset for declaration %{public}@: %{public}@"
- "v20@?0B8@\"NSError\"12"
```
