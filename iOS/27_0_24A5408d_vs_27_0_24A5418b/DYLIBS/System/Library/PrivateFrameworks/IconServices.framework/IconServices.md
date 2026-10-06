## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x666ec` | `0x668f4` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0x3cb3` | `0x3d2c` | **`+0x79`** |
| `__TEXT.__gcc_except_tab` | `0x650` | `0x6b8` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x19d0` | `0x19d8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-792.100.0.0.0
+792.102.0.0.0

-  Symbols:   4961
-  CStrings:  1077
+  Symbols:   4962
+  CStrings:  1079
Symbols:
+ GCC_except_table30
+ ___block_descriptor_80_e8_32s40s48s56bs64bs72r_e14_"NSError"8?0lr72l8s32l8s40l8s56l8s48l8s64l8
- ___block_descriptor_72_e8_32s40s48s56bs64r_e14_"NSError"8?0lr64l8s32l8s40l8s56l8s48l8
Functions:
~ -[ISConcreteIcon generateImageWithDescriptor:] : 368 -> 388
~ ___46-[ISConcreteIcon generateImageWithDescriptor:]_block_invoke : 512 -> 752
~ -[ISConcreteIcon generateImageWithDescriptor:completion:] : 540 -> 560
~ ___57-[ISConcreteIcon generateImageWithDescriptor:completion:]_block_invoke.24 : 296 -> 536
CStrings:
+ "18:57:09"
+ "Exception encoding generation request for %@ - %@: %@"
+ "Exception encoding generation request for %@ - %@: %@. Request: %@"
- "23:13:26"
```
